<script setup lang="ts"></script>

<template>
  <nav class="bg-transparent flex justify-between text-white px-5 md:px-14">
    <div class="flex justify-center items-center">
      <span class="uppercase text-3xl font-bold"> AR </span>
    </div>

    <div class="items-center flex-row gap-6 hidden md:flex">
      <ul class="flex justify-center items-center gap-6">
        <li><a class="font-bold hover:text-gray-400" href="#">Home</a></li>
        <li>
          <a class="font-bold hover:text-gray-400" href="#aboutme">About Me</a>
        </li>
        <li><a class="font-bold hover:text-gray-400" href="#skills">Skills</a></li>
        <li><a class="font-bold hover:text-gray-400" href="#">Projects</a></li>
      </ul>
      <div class="flex justify-center items-center mr-2">
        <button
          type="button"
          class="mt-3 text-white bg-red-600 hover:bg-red-500 focus:ring-4 focus:outline-none focus:ring-red-400 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-[#3b5998]/55 mr-2 mb-2"
        >
          <box-icon type="solid" name="file-pdf" color="#ffffff"></box-icon>
          Download my CV
        </button>
      </div>
    </div>

    <div class="flex justify-center items-center text-white md:hidden">
        <box-icon name='menu' color="#ffffff"></box-icon>
    </div>
  </nav>
</template>

<style scoped></style>
