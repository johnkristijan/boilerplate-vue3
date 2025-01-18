<template>
  <div id="app">
    <!-- Header with Navigation Links -->
    <header class="bg-gray-800 text-white p-4">
      <nav class="flex justify-between">
        <router-link to="/" class="text-white hover:underline">
          Home
        </router-link>
        <router-link to="/about" class="text-white hover:underline">
          About
        </router-link>
      </nav>
    </header>

    <!-- Main Content -->
    <main class="p-4">
      <router-view />
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white p-4 mt-auto text-center">
      &copy; 2025 My Vue App
    </footer>
  </div>
</template>

<script setup>
// No additional setup required for now
</script>

<style>
/* Global styles for the app */
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

body {
  margin: 0;
  font-family: "Arial", sans-serif;
  background-color: #f9f9f9;
}
</style>
