<script setup>
import { RouterView } from 'vue-router'
import './assets/base.css'
import NavBar from './components/NavBarComponet.vue'
import FooterComponent from './components/FooterComponent.vue'
</script>

<template>
  <header>
    <div>
      <NavBar />
    </div>
  </header>
  <RouterView />
  <FooterComponent />
</template>

<style scoped></style>
