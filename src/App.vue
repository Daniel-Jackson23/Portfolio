<script setup>
import { RouterLink, RouterView } from 'vue-router'
import './assets/base.css'
import NavBar from './components/NavBar.vue'
</script>

<template>
  <header>
    <div>
    <NavBar />
    </div>
  </header>
  <RouterView />
</template>

<style scoped></style>
