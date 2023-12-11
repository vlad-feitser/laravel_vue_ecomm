<template>
  <GuestLayout title="Set new Password">
    <form class="space-y-2" action="#" method="POST">
      <label for="new-password" class="block text-sm font-medium leading-6 text-gray-900">New Password</label>
      <div class="">
          <input id="new-password" name="password" type="password" required="" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
      </div>

      <label for="password_confirmation" class="block text-sm font-medium leading-6 text-gray-900">Repeat Password</label>
      <div class="">
          <input id="password_confirmation" name="password_confirmation" type="password" required="" class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
      </div>

      <div class="flex">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" class="w-5 mr-2" className="w-6 h-6">
          <path strokeLinecap="round" strokeLinejoin="round" d="M10.5 19.5L3 12m0 0l7.5-7.5M3 12h18" />
        </svg>

        <router-link :to="{name: 'login'}" class="font-semibold block my-4 text-indigo-600 hover:text-indigo-500">Back to Login</router-link>
      </div>

      <div>
        <button type="submit" class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Submit</button>
      </div>
    </form>
  </GuestLayout>
</template>

<script setup>
import GuestLayout from "../components/GuestLayout.vue"
</script>