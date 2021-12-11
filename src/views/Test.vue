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
                class="rounded-lg bg-sky-600 hover:bg-sky-800 py-2 px-8 font-bold text-center focus:ring-2 focus:ring-gray-400 inline-flex items-center">
          Get Started
        </button>
      </div>
    </nav>
  </header>

  <!--  section 1-->
    <section class="w-full bg-gray-900 h-screen flex flex-row overflow-hidden">
      <div class="flex flex-row w-full">

        <div class="bg-white w-2/5 h-2/5 m-5 mt-10 rounded-xl"></div>
        <div class="bg-white w-1/5 h-2/5 m-5 mt-10 rounded-xl"></div>
        <div class="bg-white w-2/5 h-2/5 m-5 mt-10 rounded-xl"></div>

      </div>
    </section>

<!--  <div class="flex flex-wrap -mx-4 overflow-hidden">-->

<!--    <div class="my-4 px-4 w-full overflow-hidden">-->
<!--      &lt;!&ndash; Column Content &ndash;&gt;-->
<!--      <div class="bg-gra w-2/5 h-2/5 m-5 mt-10 rounded-xl"></div>-->
<!--    </div>-->

<!--    <div class="my-4 px-4 w-full overflow-hidden">-->
<!--      &lt;!&ndash; Column Content &ndash;&gt;-->
<!--    </div>-->

<!--  </div>-->
</template>
