<template>
    <AppHeader/>
    <main class="">
      <slot>

      </slot>
    </main>
    <AppFooter/>
</template>

<script setup>
import {ref} from "vue";

</script>

<style scoped>
.body {
  background-color: #1b2132;
  min-height: 100vh;
}
</style>