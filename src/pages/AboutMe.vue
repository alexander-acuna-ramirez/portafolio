<script setup lang="ts"></script>

<template>
  <section class="h-max md:mt-20" id="aboutme">
    <div
      class="container h-full flex justify-center items-center mx-auto px-5 flex-col md:px-14"
    >
      <div class="w-full my-7">
        <span class="text-center text-white font-bold text-sm block"
          >Who I am?</span
        >
        <h2 class="text-2xl font-bold text-red-600 text-center md:text-5xl">
          About Me 🚀
        </h2>
      </div>
      <div class="w-full flex justify-center items-center flex-col md:flex-row">
        <div
          class="w-full flex justify-center flex-col bg-gray-900 rounded-lg p-3 animate__animated animate__fadeInRight"
        >
          <p class="text-gray-500 text-sm text-justify md:text-base">
            Hello! My name is Alexander and I enjoy creating things that connect
            people. My interest in web development started back in 2019 when I
            started my career in Information Systems.
          </p>
          <h5 class="text-lg font-bold text-red-600">My Experience</h5>
          <ul class="">
            <li>
              <h6 class="text-gray-400 font-semibold">ByteSoluciones (1 year)</h6>
              <p class="text-gray-500 text-sm md:text-lg text-justify">
                I worked as a FullStack Developer, I was in charge of solving
                bugs and implementing new features to the existing systems.
              </p>
              <span
                class="bg-blue-100 text-blue-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-red-600 dark:text-white"
                >Laravel</span
              >
              <span
                class="bg-blue-100 text-blue-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-green-700 dark:text-white"
                >Vue.js</span
              >
              <span
                class="bg-blue-100 text-blue-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-blue-900 dark:text-blue-300"
                >MySQL</span
              >

            </li>
            <li class="mt-5">
              <h6 class="text-gray-400 font-semibold">Computer Office of UCSM</h6>
              <p class="text-gray-500 text-sm md:text-lg text-justify">
                I built a mobile aplication for the attendance of doctors in my university.
              </p>
              <span
                class="bg-sky-400 text-blue-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-sky-400 dark:text-sky-900"
                >Ionic</span
              >
              <span
                class="bg-blue-100 text-blue-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-green-700 dark:text-white"
                >Vue.js</span
              >
            </li>
          </ul>
        </div>
        <div class="w-full flex justify-center items-center my-6 md:my-0">
          <img class="rounded-lg w-5/6" src="../assets/img/me2.jpg" alt="" />
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
