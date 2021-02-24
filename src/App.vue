<template>
  <p class="hey">Hey there {{ username }}!</p>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  setup () {
    return {
      username: 'gnuletik'
    }
  }
})
</script>

<style>
.hey {
  color: white;
  background: black;
}
</style>
