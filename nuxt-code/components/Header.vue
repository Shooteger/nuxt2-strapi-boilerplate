<template>
  <header>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg shadow-md py-2 bg-white relative flex items-center w-full justify-between">
    <div class="px-6 w-full flex flex-wrap items-center justify-between">
      <div class="navbar-collapse collapse grow items-center" id="navbarSupportedContentY">
        <ul class="navbar-nav mr-auto lg:flex lg:flex-row">
          <li class="nav-item">
            <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out" href="#!" data-mdb-ripple="true" data-mdb-ripple-color="light">Home</a>
          </li>
          <li class="nav-item mb-2 lg:mb-0">
            <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out" href="https://www.mpsysllc.com" data-mdb-ripple="true" data-mdb-ripple-color="light" target="_blank">MP SYS</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Navbar -->

  <div class="text-center bg-gray-50 text-gray-800 mt-20">
    <h1 class="text-5xl font-bold">Nuxt2 & Strapi v4 Boilerplate</h1>
    <h3 class="text-3xl font-bold mt-8">With Tailwind CSS and Axios</h3>
    <nuxt-link class="inline-block px-6 py-2.5 mt-10 bg-blue-600 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out" data-mdb-ripple="true" data-mdb-ripple-color="light" to="" role="button">View GitHub</nuxt-link>
  </div>
</header>
</template>

<script>
export default {
};
</script>

<style scoped>
</style>