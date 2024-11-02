<script setup>
import AboutUs1 from "/img/AboutUs1.png";
import AboutUs2 from "/img/AboutUs2.png";
</script>
<template>
  <div
    class="flex flex-col max-w-screen-xl px-4 py-8 mx-auto lg:flex-row lg:gap-8 xl:gap-0 lg:py-16"
  >
    <div class="flex-1 mr-auto place-self-center">
      <h2 class="text-4xl tracking-tight font-bold text-[#232536]">
        Our team of creatives
      </h2>
      <h3 class="text-2xl tracking-tight font-semibold text-[#232536] my-6">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt.
      </h3>
      <p
        class="max-w-2xl mb-6 font-medium text-gray-500 lg:mb-8 md:text-lg lg:text-xl"
      >
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat.
      </p>
    </div>
    <div class="flex-1 hidden lg:flex lg:mt-0 ms-20">
      <img :src="AboutUs1" alt="mockup" />
    </div>
  </div>
  <div
    class="flex flex-col max-w-screen-xl px-4 py-8 mx-auto lg:flex-row lg:gap-8 xl:gap-0 lg:py-16"
  >
    <div class="flex-1 hidden lg:flex lg:mt-0">
      <img :src="AboutUs2" alt="mockup" />
    </div>
    <div class="flex-1 place-self-center ms-20">
      <h2 class="text-4xl tracking-tight font-bold text-[#232536]">
        Why we started this Blog
      </h2>
      <h3 class="text-2xl tracking-tight font-semibold text-[#232536] my-6">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt.
      </h3>
      <p
        class="max-w-2xl mb-6 font-medium text-gray-500 lg:mb-8 md:text-lg lg:text-xl"
      >
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat.
      </p>
    </div>
  </div>
</template>
