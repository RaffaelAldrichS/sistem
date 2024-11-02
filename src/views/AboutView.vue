<script setup lang="ts">
import AboutSection from "@/components/AboutSection.vue";
import AboutUsHeader from "@/components/AboutUsHeader.vue";
import AuthorLists from "@/components/AuthorLists.vue";
import JoinOurTeam from "@/components/JoinOurTeam.vue";
import { ref } from "vue";

const about_authors = ref([
  {
    name: "Floyd Miles",
    jobs: "Content Writer @Company",
    image: "Author1.png",
  },
  {
    name: "Dianne Russell",
    jobs: "Content Writer @Company",
    image: "Author2.png",
  },
  {
    name: "Jenny Wilson",
    jobs: "Content Writer @Company",
    image: "Author3.png",
  },
  {
    name: "Leslie Alexander",
    jobs: "Content Writer @Company",
    image: "Author4.png",
  },
  {
    name: "Guy Hawkins",
    jobs: "Content Writer @Company",
    image: "Author5.png",
  },
  {
    name: "Eleanor Pena",
    jobs: "Content Writer @Company",
    image: "Author6.png",
  },
  {
    name: "Robert Fox",
    jobs: "Content Writer @Company",
    image: "Author7.png",
  },
  {
    name: "Jacob Jones",
    jobs: "Content Writer @Company",
    image: "Author8.png",
  },
]);
</script>

<template>
  <AboutUsHeader />
  <AboutSection />
  <AuthorLists :authors="about_authors" />
  <JoinOurTeam />
</template>
