<template>
  <div id="app">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
export default {
  name: "app",
  components: { AppHeader },
};
</script>

<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>
