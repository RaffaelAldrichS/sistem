<script setup lang="ts">
import AboutHome from "@/components/AboutHome.vue";
import AuthorLists from "@/components/AuthorLists.vue";
import ChooseCategories from "@/components/ChooseCategories.vue";
import FeaturedPost from "@/components/FeaturedPost.vue";
import HomeHero from "@/components/HomeHero.vue";
import JoinOurTeam from "@/components/JoinOurTeam.vue";
import LogoComponent from "@/components/LogoComponent.vue";
import SpecialPost from "@/components/SpecialPost.vue";
import TestimonialsView from "@/components/TestimonialsView.vue";
import { ref } from "vue";

const home_authors = ref([
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
]);
</script>

<template>
  <HomeHero />
  <FeaturedPost />
  <AboutHome />
  <ChooseCategories />
  <SpecialPost />
  <AuthorLists :authors="home_authors" />
  <LogoComponent />
  <TestimonialsView />
  <JoinOurTeam />
</template>
