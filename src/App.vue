<script>
import TheHeader from "@/components/TheHeader.vue";

  export default {
    components: {
      TheHeader
    }

  }
</script>

<template>
  <div id="app">
    <TheHeader />

    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<style>
.page {
max-width: 400px;
margin: auto;
}
</style>