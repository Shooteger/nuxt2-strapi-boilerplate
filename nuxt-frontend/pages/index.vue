<template>
  <section>
    <Hero />
    <div>{{ pages }}</div>
    <Footer />
  </section>
</template>

<script>
//import axios from "axios";

export default {
  data () {
    return {
      pages: []
    }
  },
  async fetch () {
    this.pages = await this.$strapi.find(
      "?populate[pageSection][populate][page]populate=*"
    );
  },
};
</script>
