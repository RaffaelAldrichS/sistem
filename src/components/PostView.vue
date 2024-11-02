<script setup>
const props = defineProps({
  post: {
    type: Object,
    required: true,
  },
});
</script>

<template>
  <section class="bg-white">
    <div
      class="gap-4 items-center py-4 xl:gap-2 md:grid md:grid-cols-2 sm:py-8"
    >
      <img
        class="h-80 dark:hidden"
        :src="props.post.image"
        alt="dashboard image"
      />
      <img
        class="h-80 hidden dark:block"
        :src="props.post.image"
        alt="dashboard image"
      />

      <div class="space-y-4 md:mt-0">
        <p
          class="font-semibold text-[#FFD050] md:text-lg tracking-wide uppercase"
        >
          {{ props.post.category }}
        </p>
        <h2 class="text-3xl tracking-tight font-bold text-[#232536]">
          {{ props.post.title }}
        </h2>
        <p class="font-light text-[#6D6E76] md:text-lg">
          {{ props.post.description }}
        </p>
      </div>
    </div>
  </section>
</template>
