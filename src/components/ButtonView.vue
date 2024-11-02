<script setup>
import { ChevronRight } from "lucide-vue-next";
import { defineProps } from "vue";

const props = defineProps({
  label: {
    type: String,
    default: "Read More",
    required: true,
  },
  icon: {
    type: Boolean,
    default: true,
  },
  to: {
    type: String,
    default: "/",
  },
});
</script>

<template>
  <RouterLink
    :to="props.to"
    class="inline-flex items-center justify-center px-8 py-3 mr-3 text-base font-medium text-center text-white bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900"
  >
    {{ props.label }}
    <ChevronRight v-if="icon" size="20" class="ml-2" />
  </RouterLink>
</template>
