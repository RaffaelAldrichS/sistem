<script setup>
import { ChevronRight } from "lucide-vue-next";
</script>

<template>
  <section id="about">
    <div class="flex flex-col mt-20 max-w-screen-xl mx-auto p-4">
      <div class="flex flex-row">
        <div class="bg-white w-2/12 h-5"></div>
        <div class="bg-yellow-400 w-7/12 h-5"></div>
        <div class="bg-blue-600 w-3/12 h-5"></div>
      </div>
      <div
        class="flex flex-col justify-between py-24 px-20 bg-[#F4F0F8] items-start md:flex-row"
      >
        <div class="text-left me-20 w-1/2">
          <h3 class="uppercase tracking-widest font-semibold">ABOUT US</h3>
          <h2 class="leading-16 text-3xl font-bold my-4">
            We are a community of content writers who share their learnings
          </h2>
          <p class="text-gray-500 my-4">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <p
            class="flex items-center font-normal text-[#FFD050] md:text-lg tracking-wide"
          >
            Read More <ChevronRight size="20" />
          </p>
        </div>
        <div class="md:mt-0 mt-8 w-1/2">
          <h3 class="uppercase tracking-widest font-semibold">Our Mission</h3>
          <h2 class="leading-16 text-2xl font-semibold my-4">
            Creating valuable content for creatives all around the world
          </h2>
          <p class="text-gray-500 mt-3">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
