<script setup>
import AuthorCard from "./AuthorCard.vue";

defineProps({
  authors: {
    type: Array,
    required: true,
  },
});
</script>
<template>
  <div
    class="max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
  >
    <h2
      class="text-2xl font-bold leading-none tracking-tight text-[#232536] md:text-3xl mb-6 text-center"
    >
      List of Authors
    </h2>

    <!-- Grid -->
    <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
      <AuthorCard
        v-for="(author, index) in authors"
        :key="index"
        :author="author"
      />
    </div>
    <!-- End Grid -->
  </div>
</template>
