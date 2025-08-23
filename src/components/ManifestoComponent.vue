<template>
  <section id="ManifestoComponent" class="py-36 px-4 text-white text-center">
    <h2 class="text-4xl md:text-6xl font-bold glitch-text mb-6">WIREBACK Manifesto</h2>

    <p class="max-w-2xl mx-auto text-lg md:text-xl leading-relaxed opacity-90 mb-8">
      The <span class="glitch-highlight">$WIREBACK</span> manifesto lays out our stance against
      robots,mindless automation and AI. If you want to understand what we’re building and why -
      start here.
    </p>

    <a
      href="https://wireback.xyz/manifesto.html"
      target="_blank"
      rel="noopener noreferrer"
      class="glitch-button inline-flex items-center justify-center gap-3 rounded w-full max-w-[260px] mx-auto px-6 py-3 text-base sm:max-w-[280px] md:w-[260px] md:text-lg"
      aria-label="Open the Wireback Manifesto (PDF)"
    >
      The Manifesto
    </a>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
.glitch-text {
  position: relative;
  color: #0ff;
  text-shadow:
    2px 0 red,
    -2px 0 blue;
  animation: glitch-flicker 2s infinite linear;
}
.glitch-highlight {
  color: #0ff;
  text-shadow:
    1px 0 red,
    -1px 0 blue;
  animation: glitch-glow 1s infinite linear;
}
@keyframes glitch-flicker {
  0% {
    text-shadow:
      2px 0 red,
      -2px 0 blue;
  }
  50% {
    text-shadow:
      -2px 0 red,
      2px 0 blue;
  }
  100% {
    text-shadow:
      2px 0 red,
      -2px 0 blue;
  }
}
@keyframes glitch-glow {
  0% {
    text-shadow: 0 0 4px #0ff;
  }
  50% {
    text-shadow:
      0 0 8px red,
      0 0 8px blue;
  }
  100% {
    text-shadow: 0 0 4px #0ff;
  }
}
</style>
