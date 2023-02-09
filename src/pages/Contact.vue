<script setup lang="ts"></script>

<template>
  <section class="h-auto md:mt-20" id="skills">
    <div
      class="container h-full flex justify-center items-center mx-auto px-5 flex-col md:px-14"
    >
      <div class="w-full my-6">
        <span class="text-center text-white font-bold text-sm block"
          >Send me a message</span
        >
        <h2 class="text-2xl font-bold text-red-600 text-center md:text-5xl">
          Contact 🚀
        </h2>
      </div>
      <div class="w-full container grid grid-cols-1 gap-3">
        <div>
          <label
            for="first_name"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Your Name</label
          >
          <input
            type="text"
            id="first_name"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="John"
            required
          />
        </div>
        <div>
          <label
            for="last_name"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Your E-mail address</label
          >
          <input
            type="text"
            id="last_name"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="example@mail.com"
            required
          />
        </div>

        <div>
          <label
            for="last_name"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Your message</label
          >

          <textarea
            type="text"
            id="last_name"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
            placeholder="I want to work with you!"
            required
            cols="30"
            rows="10"
          ></textarea>
        </div>
        <div class="flex justify-end">
            <button
              type="button"
              class="text-white bg-[#f30000] hover:bg-[#f30000]/90 focus:ring-4 focus:outline-none focus:ring-[#f30000]/50 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-[#3b5998]/55 mr-2 mb-2"
            >
            <box-icon name='rocket'  color='#fdf8f8' ></box-icon>
              Enviar
            </button>
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
