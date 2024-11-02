<script setup>
import { ref } from "vue";
import HomePost from "./HomePost.vue";
const posts = ref([
  {
    author: "John Doe",
    publish: "Aug 23, 2021",
    title: "8 Figma design systems that you can download for free today.",
  },
  {
    author: "Jane Smith",
    publish: "Aug 20, 2021",
    title: "Top 5 tips for designing a user-friendly interface in Figma.",
  },
  {
    author: "Mike Johnson",
    publish: "Aug 17, 2021",
    title: "10 design tips for creating engaging content in Figma.",
  },
  {
    author: "Sarah Brown",
    publish: "Aug 14, 2021",
    title: "7 effective ways to improve your team's collaboration in Figma.",
  },
]);
</script>
<template>
  <section class="flex flex-col mt-20 max-w-screen-xl mx-auto p-4">
    <div class="mt-8 max-md:max-w-full">
      <div class="flex md:flex-row flex-col gap-5">
        <article class="flex flex-col w-[59%] max-md:ml-0 max-md:w-full">
          <h2 class="text-4xl font-bold tracking-tight my-4">Featured Post</h2>
          <div
            class="flex flex-col items-start p-8 mx-auto w-full font-bold shadow-lg max-md:px-5 max-md:mt-8 max-md:max-w-full"
          >
            <img
              loading="lazy"
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/c651b39fb6730526c376a0d7d125fa0443fc8b0fa3d16aa41cb74d28393efb65?placeholderIfAbsent=true&apiKey=9b496c92d7094d298e9ef9f44f40da42"
              alt="Featured post image"
              class="object-contain self-stretch w-full aspect-[1.9] max-md:max-w-full"
            />
            <p class="mt-8 text-sm font-medium leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l May 23, 2022
            </p>
            <h3
              class="self-stretch mt-4 text-3xl tracking-tighter leading-10 text-gray-800 max-md:max-w-full"
            >
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor.
            </h3>
            <p class="mt-4 text-base leading-7 text-zinc-500 max-md:max-w-full">
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
            <a
              href="#"
              class="gap-3 px-12 py-4 mt-8 text-lg leading-none text-white bg-blue-600 max-md:px-5"
            >
              Read More &gt;
            </a>
          </div>
        </article>
        <aside class="flex flex-col ml-5 w-[41%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col grow max-md:mt-8 max-md:max-w-full">
            <h2 class="text-4xl font-bold tracking-tight my-4">All Post</h2>
            <HomePost
              v-for="(post, index) in posts"
              :key="index"
              :post="post"
            />
          </div>
        </aside>
      </div>
    </div>
  </section>
</template>
