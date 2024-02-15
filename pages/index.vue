<script setup lang="ts">

import About from "~/pages/about.vue";
import Services from "~/pages/services.vue";
import Portfolio from "~/pages/portfolio.vue";
</script>

<template>
  <navbar />
  <div class="bg-black w-full h-screen">
      <div class="lg:flex h-full w-full">
        <div class="w-6/12 lg:grid content-center mx-auto lg:mx-20">
          <div class="lg:border-l-4 border-blue-400 lg:px-10 lg:h-full">
            <h5 class="text-white text-xl">Hello, my name is</h5>
            <h1 class="text-white font-bold text-6xl py-5">IBRA SAHRIAN</h1>
            <h5 class="text-white text-xl">I'am Software Engineer</h5>
            <h5 class="text-white text-xl pb-5">Fullstack Web Developer And Android Developer</h5>
            <a href="#" class="text-white text-xl">Download CV</a>
          </div>
        </div>
        <div class="w-6/12 lg:h-full grid place-items-center mx-auto">
          <img src="/ibra.png" alt="profile" class="lg:h-5/6 lg:w-4/6">
        </div>
      </div>
  </div>
  <about/>
  <services/>
  <portfolio/>
</template>

<style scoped>

</style>