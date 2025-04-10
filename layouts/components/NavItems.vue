<template>
  <nav class="text-black font-mono">
    <ul>
      <li class="mx-2">
        <nuxt-link class="link" to="/about">About</nuxt-link>
      </li>
      <li>
        <nuxt-link class="link" to="/projects">Projects</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script setup></script>

<style scoped>
.link {
  @apply hover:bg-gray-200 p-1 rounded-md;
}

li {
  display: inline-block;
}
</style>
