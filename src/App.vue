<template>
  <div id="app" class="h-screen flex flex-col bg-gray-300">
    <header class="w-full">
      <nav class="flex justify-between items-center pt-3 pb-1 px-4">
        <div class="">
          <svg viewBox="0 0 20 20" fill="currentColor" class="w-8 h-8 fill-current text-gray-700">
            <path
              fill-rule="evenodd"
              d="M9.707 16.707a1 1 0 01-1.414 0l-6-6a1 1 0 010-1.414l6-6a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l4.293 4.293a1 1 0 010 1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </div>
        <div class="flex relative">
          <svg
            viewBox="0 0 20 20"
            fill="currentColor"
            class="w-8 h-8 mr-3 fill-current text-gray-700"
          >
            <path
              fill-rule="evenodd"
              d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
              clip-rule="evenodd"
            />
          </svg>
          <div class="static">
            <svg viewBox="0 0 20 20" fill="currentColor" class="w-8 h-8 fill-current text-gray-700">
              <path
                d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
              />
            </svg>
            <span
              class="bg-green-300 h-4 w-4 rounded-full absolute right-0 bottom-0 text-xs font-bold flex justify-center items-center"
            >2</span>
          </div>
        </div>
      </nav>
      <div class="h-56 px-4 text-gray-700 flex flex-col">
        <div>
          <p class="text-sm font-semibold">Hamburguesas</p>
          <h2 class="text-lg font-bold">Burger cangreburger</h2>
        </div>
        <div class="h-full flex">
          <div class="pl-4 pb-8 w-5/12 flex flex-col justify-end">  
            <p class="text-sm font-semibold">Price</p>
            <h2 class="text-lg font-bold">12€</h2>
          </div>
          <div class="w-7/12 flex justify-center items-end">
            <div class="h-48 w-48 flex items-end">
              <img class=" -mb-6 z-10 h-auto w-full" src="@/assets/img/burger.png" alt="burger">
            </div>
          </div>
        </div>
      </div>
    </header>
    <div class="bg-white flex-grow rounded-tr-xxl rounded-tl-xxl p-4">
      <h3>Burger cangreburger</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {},
};
</script>
