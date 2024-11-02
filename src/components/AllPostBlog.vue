<script setup>
import { ref } from "vue";
import PostView from "./PostView.vue";
import { ChevronLeft, ChevronRight } from "lucide-vue-next";

const posts = ref([
  {
    category: "Startup",
    title: "Design tips for designers that cover everything you need",
    description:
      "Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.",
    image: "/img/Blog2.png",
  },
  {
    category: "Business",
    title: "How to build rapport with your web design clients",
    description:
      "Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.",
    image: "/img/Blog3.png",
  },
  {
    category: "Startup",
    title: "Logo design trends to avoid in 2022",
    description:
      "Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.",
    image: "/img/Blog4.png",
  },
  {
    category: "Technology",
    title: "8 Figma design systems you can download for free today",
    description:
      "Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.",
    image: "/img/Blog5.png",
  },
  {
    category: "Economy",
    title: "Font sizes in UI design: The complete guide to follow",
    description:
      "Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.",
    image: "/img/Blog2.png",
  },
]);
</script>

<template>
  <div
    class="max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
  >
    <h2
      class="text-2xl font-bold leading-none tracking-tight text-[#232536] md:text-3xl"
    >
      All posts
    </h2>
    <hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-400" />
    <PostView v-for="(post, index) in posts" :key="index" :post="post" />
    <div class="flex justify-center w-full mt-16">
      <!-- Previous Button -->
      <a
        href="#"
        class="flex items-center justify-center px-3 h-8 me-3 text-md font-medium text-gray-700 hover:text-gray-900"
      >
        <ChevronLeft size="20" />
        Previous
      </a>
      <a
        href="#"
        class="flex items-center justify-center px-3 h-8 text-md font-bold text-gray-700 hover:text-gray-900"
      >
        Next
        <ChevronRight size="20" />
      </a>
    </div>
  </div>
</template>
