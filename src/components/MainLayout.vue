<script setup lang="ts">
import Footer from './partials/Footer.vue';
import Header from './partials/Header.vue';
import Sidebar from './partials/Sidebar.vue';
</script>

<template>
  <div class="min-h-screen flex flex-col">
    <Header />
    <main class="flex-1 flex flex-row">
      <Sidebar />
      <div class="flex-1">
        <slot></slot>
      </div>
    </main>
    <Footer />
  </div>
</template>
