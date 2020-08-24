<template>
  <div  class="w-full h-full">
    <p>The dog went {{activities[0]}} + {{activities[1]}} </p>

  </div>
</template>

<style>

</style>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      activities: ['poop', 'pee']
    }
  }
})
</script>
