<template>
  <div class="container p-2 mx-auto max-w-2xl">
    <header class="flex justify-between items-center py-1">
      <div class="text-xl font-semibold">
        <nuxt-link class="hover:bg-gray-200 p-1 rounded-md" to="/"
          >Amir Alimardani
        </nuxt-link>
      </div>
      <NavItems />
    </header>
    <main class="P-2">
      <slot />
    </main>
  </div>
</template>

<script setup lang="ts">
import NavItems from "./components/NavItems.vue"
</script>
