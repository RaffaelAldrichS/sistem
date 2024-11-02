<script setup>
import { ref } from "vue";
import CardComponent from "./CardComponent.vue";

// Import ikon dari Lucide
import {
  Building2,
  Rocket,
  ChartNoAxesCombined,
  BrainCircuit,
} from "lucide-vue-next";

const categories = ref([
  {
    title: "Business",
    description: "Lorem ipsum dolor sit amet, consectetuer adipiscing elit.",
    icon: Building2,
  },
  {
    title: "Startup",
    description: "Lorem ipsum dolor sit amet, consectetuer adipiscing elit.",
    icon: Rocket,
  },
  {
    title: "Economy",
    description: "Lorem ipsum dolor sit amet, consectetuer adipiscing elit.",
    icon: ChartNoAxesCombined,
  },
  {
    title: "Technology",
    description: "Lorem ipsum dolor sit amet, consectetuer adipiscing elit.",
    icon: BrainCircuit,
  },
]);
</script>

<template>
  <div
    class="max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
  >
    <h2
      class="text-2xl font-bold leading-none tracking-tight text-[#232536] md:text-3xl mb-6"
    >
      All Categories
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
      <CardComponent
        v-for="(category, index) in categories"
        :key="index"
        :category="category"
      />
    </div>
  </div>
</template>
