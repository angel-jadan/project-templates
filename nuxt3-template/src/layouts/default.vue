<template>
  <div class="min-h-screen bg-gray-100">
    <header class="bg-white shadow">
      <nav class="container mx-auto px-4 py-4"></nav>
    </header>

    <main class="container mx-auto px-4 py-8">
      <slot />
    </main>

    <footer class="bg-white shadow mt-auto">
      <div class="container mx-auto px-4 py-4"></div>
    </footer>
  </div>
</template>

<script setup lang="ts"></script>
