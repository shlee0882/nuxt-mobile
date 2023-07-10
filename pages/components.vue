<template>
  <div class="flex">
    <Sidebar />
    <main class="w-full p-6">
      <p class="text-lg mb-4">
        components page1.
      </p>
      <p class="text-lg">
        components page2.
      </p>
    </main>
  </div>
</template>

<script>
import Sidebar from '~/components/Sidebar.vue';

export default {
  components: {
    Sidebar
  }
}
</script>


