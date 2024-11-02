<script setup lang="ts">
import ButtonView from "./ButtonView.vue";
</script>

<template>
  <section class="bg-white">
    <div class="py-8 px-4 mx-auto max-w-xl text-center lg:py-16 lg:px-12">
      <h1
        class="mb-4 text-2xl font-bold tracking-tight leading-none text-[#232536] md:text-3xl lg:text-4xl"
      >
        Join our team to be a part of our story
      </h1>
      <p class="mb-8 text-lg font-normal text-[#6D6E76] lg:text-xl">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt.
      </p>
      <div
        class="flex flex-col mb-8 lg:mb-16 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4"
      >
        <ButtonView label="Join Now" :icon="false" />
      </div>
    </div>
  </section>
</template>
