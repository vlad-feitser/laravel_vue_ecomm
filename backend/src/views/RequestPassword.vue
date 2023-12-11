<template>
  <GuestLayout title="Request New Password">
    <form class="space-y-6" action="#" method="POST">
      <div>
          <input id="email" name="email" type="email" autocomplete="email" required="" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" placeholder="Email address"/>
      </div>

      
      <router-link :to="{name: 'login'}" class="font-semibold block my-4 text-indigo-600 hover:text-indigo-500">Remember  your password?</router-link>

      <div>
        <button type="submit" class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Submit</button>
      </div>
    </form>
  </GuestLayout>
</template>

<script setup>
import GuestLayout from "../components/GuestLayout.vue"
</script>