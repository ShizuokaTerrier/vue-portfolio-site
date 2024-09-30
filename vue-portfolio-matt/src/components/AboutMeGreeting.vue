<script setup lang="ts">
import heroIMG from '../assets/matt-keighley.png';
</script>

<template>
  <div class="flex flex-row items-center justify-center h-screen">
    <img :src="heroIMG" alt="" />
    <div class="pl-6">
      <h2 class="pb-4">
        Hi, I'm <span class="font-bold">Matt Keighley</span><br />
        A <span class="font-bold">fullstack software engineer</span>.
      </h2>
      <h4 class="italic">
        Born in America, raised in the UK, seasoned in Japan.
      </h4>
    </div>
  </div>
</template>
