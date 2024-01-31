<script>
import { createApp, ref } from 'vue'

export default {
  setup() {
    const count = ref(0);

    return {
      count
    };
  }
}
</script>

<template>
  <div id="app">
    <button @click="count++">
      Count is: {{ count }}
    </button>
  </div>
</template>