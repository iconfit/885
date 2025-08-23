<script setup lang="ts">
import HeroComponent from './components/HeroComponent.vue'
import TokenomicsComponent from './components/TokenomicsComponent.vue'
import LoreComponent from './components/LoreComponent.vue'
import SocialsComponent from './components/SocialsComponent.vue'
import BuyComponent from './components/BuyComponent.vue'
import ScrollToTopComponent from './components/ScrollToTopComponent.vue'
import TopbarComponent from './components/TopbarComponent.vue'
import ManifestoComponent from './components/ManifestoComponent.vue'
</script>

<template>
  <main class="bg-black text-white">
    <TopbarComponent />
    <HeroComponent />
    <section class="bg-moon-stars-edit-img">
      <ManifestoComponent />
      <TokenomicsComponent />
      <LoreComponent />
      <BuyComponent />
      <SocialsComponent />
    </section>
  </main>
  <ScrollToTopComponent />
</template>
