<template>
  <div class="w-[200px] transition-all bg-indigo-700 text-gray-200 py-4 px-2">
    <router-link :to="{name: 'app.dashboard'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2"> <HomeIcon class="w-5"/> </span>
      <span class="">Dashboard</span>
    </router-link>

    <router-link :to="{name: 'app.products'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2"> <ShoppingCartIcon class="w-5"/> </span>
      <span class="">Products</span>
    </router-link>

    <router-link :to="{name: 'app.dashboard'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2"> <UserIcon class="w-5"/> </span>
      <span class="">Users</span>
    </router-link>

    <router-link :to="{name: 'app.dashboard'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
      <span class="mr-2"> <ChartPieIcon class="w-5"/> </span>
      <span class="">Reports</span>
    </router-link>
  </div>
</template>

<script setup>
import {HomeIcon, ShoppingCartIcon, UserIcon, ChartPieIcon} from '@heroicons/vue/24/outline'

</script>

<style scoped>

</style>