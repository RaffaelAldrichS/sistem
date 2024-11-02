<script setup>
import ButtonView from "./ButtonView.vue";
import Blog1 from "/img/Blog1.png";
</script>
<template>
  <section class="bg-white dark:bg-[#F4F0F8]">
    <div
      class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
    >
      <div class="mr-auto place-self-center lg:col-span-7 pe-16">
        <p
          class="max-w-2xl font-semibold text-[#232536] uppercase tracking-wide"
        >
          Featured Post
        </p>
        <h1
          class="max-w-3xl my-6 text-3xl font-bold tracking-tight leading-none md:text-3xl xl:text-4xl dark:text-[#232536]"
        >
          Step-by-step guide to choosing great font pairs
        </h1>
        <p class="text-base text-[#4C4C4C] tracking-wide mb-4">
          By <span class="text-[#FFD050]">John Doe</span> | May 23, 2022
        </p>
        <p
          class="max-w-2xl mb-6 font-light text-[#6D6E76] lg:mb-8 md:text-lg lg:text-xl"
        >
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
          dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident.
        </p>
        <ButtonView :to="'/blogpost'" />
      </div>
      <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
        <img :src="Blog1" alt="mockup" />
      </div>
    </div>
  </section>
</template>
