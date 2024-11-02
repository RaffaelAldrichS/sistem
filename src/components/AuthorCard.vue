<script setup>
import { Facebook, Instagram, Linkedin, Twitter } from "lucide-vue-next";

const props = defineProps({
  author: {
    type: Object,
    required: true,
  },
});
</script>
<template>
  <div
    class="w-full max-w-sm bg-[#F4F4F4] hover:bg-[#FBF6EA] border rounded-lg shadow-md"
  >
    <div class="flex flex-col items-center py-10">
      <img
        class="w-24 h-24 mb-3 rounded-full shadow-lg"
        :src="`/img/${props.author.image}`"
        alt="Bonnie image"
      />
      <h5 class="mb-1 text-2xl font-bold text-[#232536]">
        {{ props.author.name }}
      </h5>
      <span class="text-sm text-[#6D6E76]">
        {{ props.author.jobs }}
      </span>
      <!-- Social Brands -->
      <div class="flex justify-center mt-4 sm:mt-0 w-full">
        <a
          class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-grey-600 hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
          href="#"
        >
          <Facebook size="16" />
        </a>
        <a
          class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-grey-600 hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
          href="#"
        >
          <Twitter size="16" />
        </a>
        <a
          class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-grey-600 hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
          href="#"
        >
          <Instagram size="16" />
        </a>
        <a
          class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-grey-600 hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
          href="#"
        >
          <Linkedin size="16" />
        </a>
      </div>
    </div>
  </div>
</template>
