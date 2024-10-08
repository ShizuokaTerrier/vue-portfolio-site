<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <div>
      <nav
        class="bg-black dark:bg-gray-900 fixed w-full z-20 top-0 start-0 shadow-lg text-white"
      >
        <div
          class="max-w-screen-xl flex flex-wrap items-center justify-around mx-auto p-4"
        >
          <RouterLink
            to="/"
            class="relative text-xl w-fit block after:block after:content-[''] after:absolute after:h-[3px] after:bg-white after:w-full after:scale-x-0 after:hover:scale-x-100 after:transition after:duration-300 after:origin-left"
            >Home</RouterLink
          >
          <RouterLink
            to="/about"
            class="relative text-xl w-fit block after:block after:content-[''] after:absolute after:h-[3px] after:bg-white after:w-full after:scale-x-0 after:hover:scale-x-100 after:transition after:duration-300 after:origin-left"
            >About Me</RouterLink
          >
          <RouterLink
            to="/portfolio"
            class="relative text-xl w-fit block after:block after:content-[''] after:absolute after:h-[3px] after:bg-white after:w-full after:scale-x-0 after:hover:scale-x-100 after:transition after:duration-300 after:origin-left"
            >Portfolio</RouterLink
          >
        </div>
      </nav>
    </div>
  </header>
  <RouterView />
</template>
