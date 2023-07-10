<template>
  <nav class="w-64 min-h-screen p-6 bg-gray-800 text-white">
    <ul>
      <li class="mb-4">
        <nuxt-link class="text-lg font-bold text-blue-500" to="/">Home</nuxt-link>
      </li>
      <li class="mb-4">
        <nuxt-link class="text-lg font-bold text-blue-500" to="/about">About</nuxt-link>
      </li>
      <li class="mb-4">
        <nuxt-link class="text-lg font-bold text-blue-500" to="/components">Components</nuxt-link>
      </li>

    </ul>
  </nav>
</template>

<script>
export default {
  name: "Sidebar"
}
</script>
