<script setup lang="ts">
import { RouterView } from 'vue-router';
import '@/assets/styles/styles.scss';
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo m-auto mt-5" src="@/assets/logo.svg" width="125" height="125" />
  </header>

  <RouterView />
</template>
