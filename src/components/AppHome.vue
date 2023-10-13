<template>
  <section class="main-section">
    <h1>JSON Tree Viewer</h1>

    <p>Simple JSON Viewer that runs completely on-client. No data exchange</p>

    <button>Load JSON</button>

    <p class="invalid" v-if="invalid">
      Invalid file. Please load a valid JSON file.
    </p>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'AppHome',
  data () {
    return {
      invalid: false
    }
  }
})
</script>
