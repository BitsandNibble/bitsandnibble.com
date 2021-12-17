<template>
  <!--  header-->
  <header class="bg-black text-white w-full">
    <nav class="container mx-auto items-center flex justify-between">
      <div>
        <ul class="flex flex-row p-4 space-x-8 font-medium">
          <li class="hover:text-red-500">Home</li>
          <li class="hover:text-red-500">About</li>
          <li class="hover:text-red-500">Contact</li>
        </ul>
      </div>

      <div>
        <svg class="h-10 mr-3" viewBox="0 0 52 72" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M1.87695 53H28.7791C41.5357 53 51.877 42.7025 51.877 30H24.9748C12.2182 30 1.87695 40.2975 1.87695 53Z"
            fill="#76A9FA"></path>
          <path
            d="M0.000409561 32.1646L0.000409561 66.4111C12.8618 66.4111 23.2881 55.9849 23.2881 43.1235L23.2881 8.87689C10.9966 8.98066 1.39567 19.5573 0.000409561 32.1646Z"
            fill="#A4CAFE"></path>
          <path
            d="M50.877 5H23.9748C11.2182 5 0.876953 15.2975 0.876953 28H27.7791C40.5357 28 50.877 17.7025 50.877 5Z"
            fill="#1C64F2"></path>
        </svg>
      </div>

      <div>
        <button type="button"
                class="rounded-lg bg-sky-600 hover:bg-sky-800 py-2 px-8 font-semibold text-center focus:ring-2 focus:ring-gray-400 inline-flex items-center">
          Get Started
        </button>
      </div>
    </nav>
  </header>

  <!--  section 1-->
  <section class="bg-gray-900 py-8 overflow-hidden">
    <div class="container mx-auto items-center">
      <div class="flex flex-row w-full h-64">
        <div class="bg-white w-2/5 rounded-xl"></div>
        <div class="w-1/5 m-5 rounded-xl"></div>
        <div class="bg-white w-2/5 rounded-xl"></div>
      </div>

      <div class="flex justify-between">
        <button
          class="my-8 px-8 font-semibold py-4 bg-sky-600 hover:bg-sky-800 focus:ring-2 focus:ring-white text-white rounded-lg">
          Get Started
        </button>

        <button
          class="my-8 px-4 py-4 bg-sky-600 hover:bg-sky-800 rounded-full">
          ⬇️
        </button>

        <div class="my-8 px-8"></div>
      </div>
    </div>
  </section>

  <section class="bg-white py-8 overflow-hidden">
    <div class="flex flex-wrap overflow-hidden container mx-auto text-black">

      <div class="my-5 w-1/3 overflow-hidden">
        <img src="images/1.jpg" class="rounded-full" alt="">
        <p class="font-semibold text-2xl mt-3 text-center uppercase">Something should be here</p>
        <p class="font-medium text-xl mt-3 text-center">Something should be here</p>
      </div>

      <div class="my-5 p-24 w-1/3 overflow-hidden">
        <!-- Column Content -->
        <img src="images/2.jpg" class="rounded-full" alt="">
      </div>

      <div class="my-5 w-1/3 overflow-hidden">
        <img src="images/3.jpg" class="rounded-full" alt="">
        <p class="font-semibold text-2xl mt-3 text-center uppercase">Something should be here</p>
        <p class="font-medium text-xl mt-3 text-center">Something should be here</p>
      </div>
    </div>
  </section>
</template>
