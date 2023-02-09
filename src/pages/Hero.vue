<script setup lang="ts">
import Navbar from "../components/layout/Navbar.vue";
</script>
<template>
  <section class="h-screen hero-background">
    <Navbar class="h-1/6 w-full container m-auto"></Navbar>
    <div class="h-5/6 container m-auto flex px-14 flex-col md:flex-row">
      <div
        class="w-full text-white flex justify-center flex-col text-center h-1/2 md:h-full md:text-left"
      >
        <h2 class="text-2xl font-bold text-red-600 md:text-5xl animate__animated animate__fadeIn">HI</h2>
        <h3 class="text-2xl font-bold md:text-5xl uppercase lg:text-7xl animate__animated animate__fadeIn">I'm Alexander</h3>
        <h3 class="text-sm font-light md:text-xl animate__animated animate__fadeIn">FullStack Developer</h3>
        <div class="mt-3">
          <button
            type="button"
            class="bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-full text-sm p-2.5 text-center inline-flex items-center mr-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
          >
            <box-icon type="logo" name="linkedin" color="#ffffff"></box-icon>
          </button>

          <button
            type="button"
            class="bg-black focus:ring-4 focus:outline-none font-medium rounded-full text-sm p-2.5 text-center inline-flex items-center mr-2"
          >
            <box-icon type="logo" name="github" color="#ffffff"></box-icon>
          </button>

          <button
            type="button"
            class="bg-green-500 focus:ring-4 focus:outline-none font-medium rounded-full text-sm p-2.5 text-center inline-flex items-center mr-2"
          >
            <box-icon
              name="whatsapp"
              type="logo"
              flip="horizontal"
              animation="tada"
              color="#ffffff"
            ></box-icon>
          </button>
        </div>
      </div>
      <div class="w-full flex justify-center items-center h-1/2 md:h-full">
        <div class="h-1/2 md:h-3/4">
          <img
            src="../assets/img/astronaut.png"
            alt="Astronaut"
            class="astronaut h-5/6 md:h-3/6 lg:h-5/6"
          />

          <img
            src="../assets/img/cola.png"
            alt="cola"
            class="cola h-2/6 md:h-1/6 lg:h-1/6"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero-gradient {
  background-color: #4158d0;
  background-image: linear-gradient(
    43deg,
    #4158d0 0%,
    #c850c0 46%,
    #ffcc70 100%
  );
}
@keyframes orbita {
  0% {
    transform: rotate(0deg) translate(0%, 0%);
  }
  25% {
    transform: rotate(90deg) translate(25%, 0%);
  }
  50% {
    transform: rotate(180deg) translate(0%, 25%);
  }
  75% {
    transform: rotate(270deg) translate(25%, 0%);
  }
  100% {
    transform: rotate(360deg) translate(0%, 0%);
  }
}
@keyframes orbita2 {
  0% {
    transform: rotate(0deg) translate(0%, 0%);
  }
  25% {
    transform: rotate(90deg) translate(0%, 25%);
  }
  50% {
    transform: rotate(180deg) translate(25%, 25%);
  }
  75% {
    transform: rotate(270deg) translate(0%, 10%);
  }
  100% {
    transform: rotate(360deg) translate(0%, 0%);
  }
}
.astronaut {
  position: relative;
  width: auto;
  animation-name: orbita;
  animation-duration: 50s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}

.cola {
  position: relative;
  width: auto;
  animation-name: orbita2;
  animation-duration: 25s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}
.hero-background {
  /*background-image: url("../assets/img/space.jpg");
  background-position: center;
  background-size: cover;*/

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
