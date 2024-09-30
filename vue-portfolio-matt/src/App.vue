<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <div>
      <nav
        class="bg-slate-300 dark:bg-gray-900 fixed w-full z-20 top-0 start-0 shadow-lg"
      >
        <div
          class="max-w-screen-xl flex flex-wrap items-center justify-around mx-auto p-4"
        >
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About Me</RouterLink>
          <RouterLink to="/portfolio">Portfolio</RouterLink>
        </div>
      </nav>
    </div>
  </header>
  <RouterView />
</template>
