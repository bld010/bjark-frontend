<template>
  <div>
    <div class="flex items-start bg-gray-100 justify-between p-3">
      <h1 class="text-4xl">bjark</h1>      
      <div class="flex w-1/4 justify-around">
        <nuxt-link to="/history" class="bg-green-700 border-2 rounded-lg p-2 text-white font-bold border-green-900 tracking-widest uppercase    ">History</nuxt-link>
        <nuxt-link to="/insights" class="bg-green-700 border-2 rounded-lg p-2 text-white font-bold border-green-900 tracking-widest uppercase    ">Insights</nuxt-link>
      </div>
    </div>
    <TodaysActivities />
  </div>


</template>

<script lang="ts">
import Vue from 'vue'


export default Vue.extend({})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

</style>
