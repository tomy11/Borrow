<template>
  <div class="pt-24">
      <div class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center">
        <!--Left Col-->
        <div class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-left">
          <p class="uppercase tracking-loose w-full">Borrow Crypto Currency</p>
          <h1 class="my-4 text-5xl font-bold leading-tight">
            บริการกู้ยืม Crypto
          </h1>
          <p class="leading-normal text-2xl mb-8">
            เราเป็นผู้ให้บริการในการกู้ยืมเหรียญ Crypto โดยสามารถใช้ Crypto ที่ท่านมีอยู่มาค้ำประกันได้
          </p>
          <button class="mx-auto lg:mx-0 hover:underline bg-white text-gray-800 font-bold rounded-full my-6 py-4 px-8 shadow-lg focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out">
            Subscribe
          </button>
        </div>
        <!--Right Col-->
        <div class="w-full md:w-3/5 py-6 text-center">
          <img class="w-full md:w-4/5 z-50" src="../../assets/image/hero.png" />
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: "Slide",
  components: {},
};
</script>