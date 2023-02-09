<script setup lang="ts"></script>

<template>
  <section class="h-auto md:mt-20" id="skills">
    <div
      class="container h-full flex justify-center items-center mx-auto px-5 flex-col md:px-14"
    >
      <div class="w-full my-6">
        <span class="text-center text-white font-bold text-sm block"
          >What are My Skills?</span
        >
        <h2 class="text-2xl font-bold text-red-600 text-center md:text-5xl">
          Skills 🚀
        </h2>
      </div>
      <div class="w-full container grid grid-cols-2 gap-6 px-5 md:grid-cols-4 md:w-3/4 md:px-0">
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" width="auto" src="../assets/img/skills/spring-boot.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/java.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/laravel.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/php.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/vue.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/Typescript.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/mysql.png" alt="">
        </div>
        <div class="bg-gray-900 rounded-lg flex justify-center items-center">
          <img class="h-3/4 md:h-2/4" src="../assets/img/skills/express.png" alt="">
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  background-color: #0c1c33;
  background-image: radial-gradient(
      white,
      rgba(255, 255, 255, 0) 2px,
      transparent 40px
    ),
    radial-gradient(white, rgba(255, 255, 255, 0) 1px, transparent 30px),
    radial-gradient(white, rgba(255, 255, 255, 0) 2px, transparent 40px),
    radial-gradient(white, rgba(255, 255, 255, 0) 2px, transparent 30px);
  background-size: 550px 550px, 350px 350px, 250px 250px, 150px 150px;
  background-position: 0 0, 40px 60px, 130px 270px, 70px 100px;
}
</style>
