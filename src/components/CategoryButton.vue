<template>
    <button class="bg-blue-400 text-white font-semibold py-3 px-4 w-full rounded-md shadow-md flex items-center justify-center">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-6 h-6 mr-2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M7 11h10M7 11h10M7 11h10M7 11h10" />
      </svg>
      {{ label }}
    </button>
  </template>
  
  <script>
  export default {
    props: ['label']
  }
  </script>
  