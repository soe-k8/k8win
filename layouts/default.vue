<template>
  <div class="h-screen">
    <AppHeader/>
    <main class="">
      <slot>

      </slot>
    </main>
    <AppFooter/>
  </div>
</template>

<script setup>
import {ref} from "vue";

</script>

<style scoped>

</style>