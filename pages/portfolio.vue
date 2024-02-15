<script setup lang="ts">
import { AdjustmentsVerticalIcon, CodeBracketIcon,  DevicePhoneMobileIcon, ServerIcon, ComputerDesktopIcon, RectangleStackIcon } from '@heroicons/vue/24/outline'
const text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer dictum dictum ligula, sed iaculis augue consectetur id. Fusce suscipit risus sed varius gravida. Vivamus accumsan neque sed libero rhoncus tincidunt."
</script>

<template>
  <div class="container mx-auto h-full bg-gray-100 py-20">
    <div class="mx-auto h-auto w-2/6 text-gray-500 p-10">
      <h1 class="font-bold lg:text-3xl text-black text-center">Our Portfolio </h1>
      <p class="text-center pt-10 pb-5">
        I Develop Services for customers, specializing in Android app, Modern Website, Web Services And Fullstack Laravel
      </p>
    </div>
    <div class="mx-48 grid grid-cols-3 place-items-stretch gap-4 py-5 text-center">
      <!--Data 1-->
      <div class="bg-white h-80 shadow-xl">
        <div class="bg-red-800 h-70 mx-2 mt-2"></div>
        <div class="h-25 mx-2 lg:grid content-center">
          <h1 class="font-bold">Project 1</h1>
          <h5>Recent Work</h5>
        </div>
      </div>
      <!--Data 2-->
      <div class="bg-white h-80 shadow-xl">
        <div class="bg-red-800 h-70 mx-2 mt-2"></div>
        <div class="h-25 mx-2 lg:grid content-center">
          <h1 class="font-bold">Project 1</h1>
          <h5>Recent Work</h5>
        </div>
      </div>
      <!--Data 3-->
      <div class="bg-white h-80 shadow-xl">
        <div class="bg-red-800 h-70 mx-2 mt-2"></div>
        <div class="h-25 mx-2 lg:grid content-center">
          <h1 class="font-bold">Project 1</h1>
          <h5>Recent Work</h5>
        </div>
      </div>
      <!--Data 4-->
      <div class="bg-white h-80 shadow-xl">
        <div class="bg-red-800 h-70 mx-2 mt-2"></div>
        <div class="h-25 mx-2 lg:grid content-center">
          <h1 class="font-bold">Project 1</h1>
          <h5>Recent Work</h5>
        </div>
      </div>
      <!--Data 5-->
      <div class="bg-white h-80 shadow-xl">
        <div class="bg-red-800 h-70 mx-2 mt-2"></div>
        <div class="h-25 mx-2 lg:grid content-center">
          <h1 class="font-bold">Project 1</h1>
          <h5>Recent Work</h5>
        </div>
      </div>
      <!--Data 6-->
      <div class="bg-white h-80 shadow-xl">
        <div class="bg-red-800 h-70 mx-2 mt-2"></div>
        <div class="h-25 mx-2 lg:grid content-center">
          <h1 class="font-bold">Project 1</h1>
          <h5>Recent Work</h5>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .h-70 {
    height: 70%;
  }
  .h-25 {
    height: 25%;
  }
</style>