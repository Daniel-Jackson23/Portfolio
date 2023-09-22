<script setup>
import { RouterView } from 'vue-router'
import './assets/base.css'
import NavBar from './components/NavBarComponet.vue'
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
