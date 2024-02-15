<script setup lang="ts">
  import { AdjustmentsVerticalIcon, CodeBracketIcon,  DevicePhoneMobileIcon, ServerIcon, ComputerDesktopIcon, RectangleStackIcon } from '@heroicons/vue/24/outline'
  const text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer dictum dictum ligula, sed iaculis augue consectetur id. Fusce suscipit risus sed varius gravida. Vivamus accumsan neque sed libero rhoncus tincidunt."
</script>

<template>
  <div class="container mx-auto h-full bg-gray-100 py-20">
    <div class="mx-auto h-auto w-2/6 text-gray-500 p-10">
      <h1 class="font-bold lg:text-3xl text-black text-center">My Services</h1>
      <p class="text-center pt-10 pb-5">
        I Develop Services for customers, specializing in Android app, Modern Website, Web Services And Fullstack Laravel
       </p>
    </div>
    <div class="mx-48 grid grid-cols-3 place-items-stretch gap-4 py-5 text-center">
      <!--Data 1-->
      <div class="group bg-white h-80 shadow-xl rounded-xl hover:bg-black">
        <AdjustmentsVerticalIcon class="w-20 p-3 rounded-full bg-sky-400 text-white mx-auto my-5 ring ring-sky-500"/>
        <h1 class="text-xl font-bold text-black group-hover:text-white">Development</h1>
        <p class="text-sm py-3 px-5 text-black group-hover:text-white">{{text}}</p>
        <a href="#" class="font-bold text-black group-hover:text-white">Read More</a>
      </div>
      <!--Data 2-->
      <div class="group bg-white h-80 shadow-xl rounded-xl hover:bg-black">
        <CodeBracketIcon class="w-20 p-3 rounded-full bg-sky-400 text-white mx-auto my-5 ring ring-sky-500" />
        <h1 class="text-xl font-bold text-black group-hover:text-white">Modern Web</h1>
        <p class="text-sm py-3 px-5 text-black group-hover:text-white">{{text}}</p>
        <a href="#" class="font-bold text-black group-hover:text-white">Read More</a>
      </div>
      <!--Data 3-->
      <div class="group bg-white h-80 shadow-xl rounded-xl hover:bg-black">
        <DevicePhoneMobileIcon class="w-20 p-3 rounded-full bg-sky-400 text-white mx-auto my-5 ring ring-sky-500" />
        <h1 class="text-xl font-bold text-black group-hover:text-white">Android App</h1>
        <p class="text-sm py-3 px-5 text-black group-hover:text-white">{{text}}</p>
        <a href="#" class="font-bold text-black group-hover:text-white">Read More</a>
      </div>
      <!--Data 4-->
      <div class="group bg-white h-80 shadow-xl rounded-xl hover:bg-black">
        <ServerIcon class="w-20 p-3 rounded-full bg-sky-400 text-white mx-auto my-5 ring ring-sky-500" />
        <h1 class="text-xl font-bold text-black group-hover:text-white">Backend Dev</h1>
        <p class="text-sm py-3 px-5 text-black group-hover:text-white">{{text}}</p>
        <a href="#" class="font-bold text-black group-hover:text-white">Read More</a>
      </div>
      <!--Data 5-->
      <div class="group bg-white h-80 shadow-xl rounded-xl hover:bg-black">
        <ComputerDesktopIcon class="w-20 p-3 rounded-full bg-sky-400 text-white mx-auto my-5 ring ring-sky-500" />
        <h1 class="text-xl font-bold text-black group-hover:text-white">Frontend Dev</h1>
        <p class="text-sm py-3 px-5 text-black group-hover:text-white">{{text}}</p>
        <a href="#" class="font-bold text-black group-hover:text-white">Read More</a>
      </div>
      <!--Data 6-->
      <div class="group bg-white h-80 shadow-xl rounded-xl hover:bg-black">
        <RectangleStackIcon class="w-20 p-3 rounded-full bg-sky-400 text-white mx-auto my-5 ring ring-sky-500" />
        <h1 class="text-xl font-bold text-black group-hover:text-white">Fullstack Dev</h1>
        <p class="text-sm py-3 px-5 text-black group-hover:text-white">{{text}}</p>
        <a href="#" class="font-bold text-black group-hover:text-white">Read More</a>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>