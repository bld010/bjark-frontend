<template>
  <div  class="w-1/2 bg-purple-500 flex justify-center items-center flex-col m-auto h-full">
    <h2 class="text-xl text-center mb-3 underline">Today's Dog Log</h2>
    <ul class="">
      <li class="flex flex-row justify-between" v-for="activity in activities" :key="activity.index">
        <img class="h-8" v-if="activity.activity == 'poop'" src="../assets/poopMoji.png">
        <img class="h-8" v-else src="../assets/pee.jpg">
        <p>{{ activity.time }}</p>
        <p>{{ activity.activity }} </p>
      </li>
    </ul>

  </div>
</template>

<style>

</style>

<script lang="ts">
import Vue from 'vue';

let activities = [
  {
    time: Date.now(),
    activity: 'poop'
  }, 
  { time: Date.now() + 1, 
    activity: 'pee'
  },
  {
    time: Date.now(),
    activity: 'poop'
  }, 
  { time: Date.now() + 1, 
    activity: 'pee'
  },
  {
    time: Date.now(),
    activity: 'poop'
  }, 
  { time: Date.now() + 1, 
    activity: 'pee'
  },
  {
    time: Date.now(),
    activity: 'poop'
  }, 
  { time: Date.now() + 1, 
    activity: 'pee'
  }
]

export default Vue.extend({
  data() {
    return {
      activities: activities
    }
  }
})
</script>
