<template>
  <AppHome />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import AppHome from './components/AppHome.vue'

export default defineComponent({
  components: {
    AppHome
  },
  name: 'App'
})
</script>

<style>
@import './assets/styles/global.css';
</style>
