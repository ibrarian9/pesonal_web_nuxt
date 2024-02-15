<script setup lang="ts">
  const text = "My name is Ibra Sahrian Alsa. I studied at the University of Uin Suska Riau. I am majoring in informatics engineering '21. " +
      "I aspire to become a Programmer So I'm really serious learning about programming, especially in the field of web development. " +
      "So I studied frontend and backend like bootstrap, tailwind, javascript, React.js and Node.js."
</script>

<template>
  <div class="container mx-auto h-screen">
    <div class="lg:flex w-full h-full">
      <div class="w-3/6 grid content-center px-20 py-5">
        <h5 class="font-bold text-xl">I'm Ibra Sahrian</h5>
        <h5 class="font-bold py-5">I'm a student at Suska Riau State Islamic University </h5>
        <p class="text-justify pb-5">{{text}}</p>
        <a href="#" class="rounded-2xl bg-gradient-to-r from-blue-500 to-cyan-500 py-2 px-3 w-36 text-center text-white ring hover:ring-white">Contact Me</a>
      </div>
      <div class="w-3/6">
        <img src="" class="h-4/5" alt="profile">
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>