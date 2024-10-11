<script setup lang="ts">
import LULU from '../assets/LULU-Frontend.png';
import FindADoc from '../assets/Find a Doc.png';
import Strive from '../assets/Strive-Frontend.png';
</script>

<template>
  <div class="mt-14 grid grid-cols-1 md:grid-cols-2">
    <div class="shadow-lg rounded-lg mb-2 mx-4 mt-6">
      <h2
        class="pt-5 px-5 mb-4 text-2xl font-semibold text-gray-900 text-center"
      >
        Listen Up Level Up
      </h2>
      <div>
        <img :src="LULU" alt="" />
      </div>
      <div class="flex flex-row justify-around p-4">
        <a
          class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-full text-sm px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700"
          href="https://github.com/ShizuokaTerrier/ListenUpLevelUpFrontEnd"
          target="_blank"
        >
          Frontend Repo
        </a>
        <a
          class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-full text-sm px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700"
          href="https://github.com/ShizuokaTerrier/ListenUp-LevelUp"
          target="_blank"
        >
          Backend Repo
        </a>
      </div>

      <p class="p-4 text-center max-w-prose mx-auto my-4">
        Listen Up Level Up is a fullStack React app designed to help English
        language learners develop their listening skills through the use of
        pronunciation awareness games.
      </p>
    </div>
    <div class="shadow-lg rounded-lg mb-2 mx-4 mt-6">
      <h2
        class="pt-5 px-5 mb-4 text-2xl font-semibold text-gray-900 text-center"
      >
        Find a Doc
      </h2>
      <div class="rounded-md">
        <img :src="FindADoc" alt="" />
      </div>
      <div class="flex flex-row justify-around p-4">
        <a
          class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-full text-sm px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700"
          href="https://github.com/ourjapanlife"
          target="_blank"
        >
          Our Japan Life Github Page
        </a>
        <a
          class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-full text-sm px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700"
          href="https://www.findadoc.jp/"
          target="_blank"
        >
          Find-a-Doc Website
        </a>
      </div>
      <p class="p-4 text-center max-w-prose mx-auto my-4">
        Find A Doc is an NPO open source project with the goal of helping all
        people in Japan, regardless of nationality and language, to navigate the
        Japanese healthcare system with confidence.
      </p>
    </div>
    <div class="shadow-lg rounded-lg mb-2 mx-4 mt-6">
      <h2
        class="pt-5 px-5 mb-4 text-2xl font-semibold text-gray-900 text-center"
      >
        Strive
      </h2>
      <div class="rounded-md">
        <img :src="Strive" alt="" />
      </div>
      <div class="flex flex-row justify-around p-4">
        <a
          class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-full text-sm px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700"
          href="https://github.com/strive-management/strive-frontend"
          target="_blank"
        >
          Frontend Repo
        </a>
        <a
          class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-full text-sm px-5 py-2.5 me-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700"
          href="https://github.com/strive-management/strive-backend"
          target="_blank"
        >
          Backend Repo
        </a>
      </div>
      <p class="p-4 text-center max-w-prose mx-auto my-4">
        Strive is a human resources web application that allows small to
        mid-sized companies manage their workforce with just the tools they need
        to get the job done and just the right price. No more paying for the
        extra bells and whistles you aren't using.
      </p>
    </div>
  </div>
</template>
