<template>
  <div class="min-h-screen flex flex-col">
    <Header />
    <main class="flex-grow p-4">
      <router-view>
      </router-view>
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue';
</script>
