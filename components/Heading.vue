<template>
  <div>
    <p>aaa</p>
    <h1>{{ text }}</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    text: {
      type: String,
      required: true,
    },
  },
})
</script>
