<template>

    <div class="flex flex-col bg-gray-100 items-center h-screen p-8">
      
      <h1 class="text-5xl">bjark</h1>

      <img src="~/assets/dog.jpg" alt="Cute tan and white puppy sitting on a deck" class="rounded-lg w-1/3 m-auto shadow-xl"> 
      
      <div class="flex w-1/3 justify-around">
        
          <nuxt-link to="/history" class="bg-green-700 border-2 rounded-lg p-2 text-white font-bold border-green-900 tracking-widest uppercase    ">History</nuxt-link>
        
          <nuxt-link to="/insights" class="bg-green-700 border-2 rounded-lg p-2 text-white font-bold border-green-900 tracking-widest uppercase    ">Insights</nuxt-link>

      </div>

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
