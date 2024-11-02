<script setup>
const props = defineProps({
  post: {
    type: Object,
    required: true,
  },
});
</script>

<template>
  <article
    class="flex flex-col items-start py-7 pr-20 pl-8 bg-white hover:bg-[#FBF6EA] max-md:px-5 max-md:max-w-full shadow-md my-2"
  >
    <p class="text-sm font-medium leading-none text-amber-300">
      By <span class="text-amber-300">{{ props.post.author }}</span>
      {{ props.post.publish }}
    </p>
    <h3 class="mt-2 text-2xl font-bold leading-8 text-gray-800">
      {{ props.post.title }}
    </h3>
  </article>
</template>
