<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Navbar from "./components/Navbar.vue";
import Home from "./components/Home.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="bg-slate-100 h-screen">
    <div class="container mx-auto px-16">
      <Navbar />
      <Home />
    </div>
  </div>
  <Footer />
</template>

<style scoped></style>
