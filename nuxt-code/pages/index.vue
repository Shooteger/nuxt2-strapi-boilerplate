<template>
  <div>
    <Header />
    <div class="container">
      <div v-if="error">
        {{ error }}
      </div>
      <ul v-else>
        <li v-for="restaurant in restaurants" :key="restaurant.id">
          {{ restaurant.attributes.name }}
        </li>
      </ul>
    </div>
    <Footer />
  </div>
</template>

<script>
import axios from "axios";

export default {
  name: "App",
  data() {
    return {
      restaurants: [],
      error: null,
    };
  },
  async mounted() {
    try {
      const response = await axios.get("http://localhost:1337/api/restaurants");
      this.restaurants = response.data.data;
    } catch (error) {
      this.error = error;
    }
  },
};
</script>
