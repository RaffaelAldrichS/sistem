<script setup>
import { RouterView } from "vue-router";
import NavigationBar from "@/components/NavigationBar.vue";
import FooterBar from "@/components/FooterBar.vue";
</script>
<template>
  <NavigationBar />
  <RouterView />
  <FooterBar />
</template>
