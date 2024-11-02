<script setup>
import Logo1 from "/img/Logo 1.png";
import Logo2 from "/img/Logo 2.png";
import Logo3 from "/img/Logo 3.png";
import Logo4 from "/img/Logo 4.png";
import Logo5 from "/img/Logo 5.png";
</script>
<template>
  <section class="bg-white">
    <div class="py-8 lg:py-16 mx-auto max-w-screen-xl px-4">
      <div
        class="grid grid-cols-2 gap-8 text-gray-500 sm:gap-12 md:grid-cols-3 lg:grid-cols-6 dark:text-gray-400"
      >
        <p class="text-[#6D6E76] block">
          We Are <span class="block text-2xl font-bold">Featured in</span>
        </p>
        <a href="#" class="flex justify-center items-center">
          <img :src="Logo1" alt="" />
        </a>
        <a href="#" class="flex justify-center items-center">
          <img :src="Logo2" alt="" />
        </a>
        <a href="#" class="flex justify-center items-center">
          <img :src="Logo3" alt="" />
        </a>
        <a href="#" class="flex justify-center items-center">
          <img :src="Logo4" alt="" />
        </a>
        <a href="#" class="flex justify-center items-center">
          <img :src="Logo5" alt="" />
        </a>
      </div>
    </div>
  </section>
</template>
