<template>
  <RouterLink
    to="/category"
    class="p-6 rounded-lg shadow transition-colors duration-200"
    :class="{
      'bg-blue-500 text-white': isActive,
      'bg-white text-gray-800': !isActive,
      'hover:bg-gray-100': !isActive,
    }"
    @click="toggleActive"
  >
    <div class="text-4xl mb-3">
      <component
        :is="props.category.icon"
        :class="`w-10 h-10  ${isActive ? 'text-gray-100' : 'text-gray-500'}`"
      />
    </div>
    <h5 class="mb-2 text-xl font-semibold">
      {{ props.category.title }}
    </h5>
    <p class="text-sm font-normal">
      {{ props.category.description }}
    </p>
  </RouterLink>
</template>

<script setup>
import { ref } from "vue";
import { defineProps } from "vue";
import { RouterLink } from "vue-router";

const props = defineProps({
  category: {
    type: Object,
    required: true,
  },
});

const isActive = ref(false);

function toggleActive() {
  isActive.value = !isActive.value;
}
</script>
