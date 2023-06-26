<script setup>
import { RouterView } from "vue-router";
import SiteFooter from "./components/SiteFooter.vue";
import SiteNavbar from "./components/SiteNavbar.vue";
</script>

<template>
  <div class="flex flex-col h-screen">
    <site-navbar />
    <main class="flex-grow">
      <RouterView />
    </main>
    <site-footer />
  </div>
</template>
