<script setup>
import HeroPic from "/img/HeroPic.png";
import ButtonView from "./ButtonView.vue";
</script>
<template>
  <section
    class="bg-cover bg-center bg-no-repeat bg-[url()] bg-gray-500 bg-blend-multiply"
    :style="{ backgroundImage: `url(${HeroPic})` }"
  >
    <div
      class="grid max-w-screen-xl px-4 py-16 mx-auto lg:gap-8 xl:gap-0 lg:py-32 lg:grid-cols-12"
    >
      <div class="mr-auto place-self-center lg:col-span-12">
        <p
          class="max-w-2xl font-semibold text-gray-200 lg:text-lg dark:text-gray-300 uppercase tracking-wide"
        >
          Posted on <span class="font-extrabold">startup</span>
        </p>
        <h1
          class="max-w-3xl my-6 text-4xl font-bold tracking-tight leading-none md:text-3xl xl:text-5xl dark:text-white"
        >
          Step-by-step guide to choosing great font pairs
        </h1>
        <p
          class="text-base text-gray-300 dark:text-gray-200 tracking-wide mb-4"
        >
          By <span class="text-blue-500">James West</span> | May 23, 2022
        </p>
        <p
          class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400"
        >
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
          dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident.
        </p>
        <ButtonView />
      </div>
    </div>
  </section>
</template>
