<script setup>
import { ref } from 'vue'

let counter = ref(0)

setInterval(() => {
  counter.value++
}, 1000)
</script>

<template>
  <div>
    <!--    <header class="bg-white shadow" v-if="$route.meta.title">-->
    <!--      <div class="px-4 py-6 mx-auto max-w-7xl sm:px-6 lg:px-8">-->
    <!--        <h1-->
    <!--          @click="counter = 0"-->
    <!--          class="text-3xl font-bold leading-tight text-gray-900"-->
    <!--        >-->
    <!--          {{ $route.meta.title }} / {{ counter }}-->
    <!--        </h1>-->
    <!--      </div>-->
    <!--    </header>-->

    <!--    header 1-->
    <!--    <header class="text-gray-400 bg-gray-900 body-font">-->
    <!--      <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">-->
    <!--        <a class="flex title-font font-medium items-center text-white mb-4 md:mb-0">-->
    <!--          <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">-->
    <!--            <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>-->
    <!--          </svg>-->
    <!--          <span class="ml-3 text-xl">Tailblocks</span>-->
    <!--        </a>-->
    <!--        <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">-->
    <!--          <a class="mr-5 hover:text-white">First Link</a>-->
    <!--          <a class="mr-5 hover:text-white">Second Link</a>-->
    <!--          <a class="mr-5 hover:text-white">Third Link</a>-->
    <!--          <a class="mr-5 hover:text-white">Fourth Link</a>-->
    <!--        </nav>-->
    <!--        <button class="inline-flex items-center bg-gray-800 border-0 py-1 px-3 focus:outline-none hover:bg-gray-700 rounded text-base mt-4 md:mt-0">Button-->
    <!--          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">-->
    <!--            <path d="M5 12h14M12 5l7 7-7 7"></path>-->
    <!--          </svg>-->
    <!--        </button>-->
    <!--      </div>-->
    <!--    </header>-->


    <!--    header 2-->
<!--    <nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800">-->
<!--      <div class="container mx-auto flex flex-wrap items-center justify-between">-->
<!--        <a href="#" class="flex">-->
<!--          <svg class="h-10 mr-3" viewBox="0 0 52 72" fill="none" xmlns="http://www.w3.org/2000/svg">-->
<!--            <path-->
<!--              d="M1.87695 53H28.7791C41.5357 53 51.877 42.7025 51.877 30H24.9748C12.2182 30 1.87695 40.2975 1.87695 53Z"-->
<!--              fill="#76A9FA"></path>-->
<!--            <path-->
<!--              d="M0.000409561 32.1646L0.000409561 66.4111C12.8618 66.4111 23.2881 55.9849 23.2881 43.1235L23.2881 8.87689C10.9966 8.98066 1.39567 19.5573 0.000409561 32.1646Z"-->
<!--              fill="#A4CAFE"></path>-->
<!--            <path-->
<!--              d="M50.877 5H23.9748C11.2182 5 0.876953 15.2975 0.876953 28H27.7791C40.5357 28 50.877 17.7025 50.877 5Z"-->
<!--              fill="#1C64F2"></path>-->
<!--          </svg>-->
<!--          <span class="self-center text-lg font-semibold whitespace-nowrap dark:text-white">FlowBite</span>-->
<!--        </a>-->
<!--        <button data-collapse-toggle="mobile-menu" type="button"-->
<!--                class="md:hidden ml-3 text-gray-500 hover:bg-gray-100focus:outline-none focus:ring-2 focus:ring-gray-200 rounded-lg text-sm p-2 inline-flex items-center dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"-->
<!--                aria-controls="mobile-menu-2" aria-expanded="false">-->
<!--          <span class="sr-only">Open main menu</span>-->
<!--          <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">-->
<!--            <path fill-rule="evenodd"-->
<!--                  d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"-->
<!--                  clip-rule="evenodd"></path>-->
<!--          </svg>-->
<!--          <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">-->
<!--            <path fill-rule="evenodd"-->
<!--                  d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"-->
<!--                  clip-rule="evenodd"></path>-->
<!--          </svg>-->
<!--        </button>-->
<!--        <div class="hidden md:block w-full md:w-auto" id="mobile-menu">-->
<!--          <ul class="flex-col md:flex-row flex md:space-x-8 mt-4 md:mt-0 md:text-sm md:font-medium">-->
<!--            <li>-->
<!--              <a href="#"-->
<!--                 class="bg-blue-700 md:bg-transparent text-white block pl-3 pr-4 py-2 md:text-blue-700 md:p-0 rounded dark:text-white"-->
<!--                 aria-current="page">Home</a>-->
<!--            </li>-->
<!--            <li>-->
<!--              <a href="#"-->
<!--                 class="text-gray-700 hover:bg-gray-50 border-b border-gray-100 md:hover:bg-transparent md:border-0 block pl-3 pr-4 py-2 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>-->
<!--            </li>-->
<!--            <li>-->
<!--              <a href="#"-->
<!--                 class="text-gray-700 hover:bg-gray-50 border-b border-gray-100 md:hover:bg-transparent md:border-0 block pl-3 pr-4 py-2 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Services</a>-->
<!--            </li>-->
<!--            <li>-->
<!--              <a href="#"-->
<!--                 class="text-gray-700 hover:bg-gray-50 border-b border-gray-100 md:hover:bg-transparent md:border-0 block pl-3 pr-4 py-2 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Pricing</a>-->
<!--            </li>-->
<!--            <li>-->
<!--              <a href="#"-->
<!--                 class="text-gray-700 hover:bg-gray-50 md:hover:bg-transparent md:border-0 block pl-3 pr-4 py-2 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Contact</a>-->
<!--            </li>-->
<!--          </ul>-->
<!--        </div>-->
<!--      </div>-->
<!--    </nav>-->

    <main>
      <router-view />
    </main>
  </div>
</template>
