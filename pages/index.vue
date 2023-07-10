<template>
  <div class="flex">
    <Sidebar />
    <main class="w-full p-6">
      <!-- Page Content Goes Here -->
      <p class="text-lg mb-4">
        main page1.
      </p>
      <p class="text-lg">
        main page2.
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
