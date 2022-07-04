<template>
  <section>
    <Hero />
    <Footer />
  </section>
</template>

<script>
import axios from "axios";

export default {
  data() {
    return {
      website: [],
      error: null,
    };
  },
  async mounted() {
    try {
      this.website = await this.$strapi.find('company-name-website?populate=*');
      /*
      const response = await axios.get("http://localhost:1337/api/company-name-website?populate=*");
      this.company = response.data;
      */
    } catch (error) {
      this.error = error;
    }
  },
};
</script>
