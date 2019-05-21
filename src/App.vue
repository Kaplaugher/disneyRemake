<template>
  <div
    id="app"
    class="flex bg-gray-900 text-white min-h-screen"
  >
    <div class="nav w-24 fixed bg-blue-500 min-h-screen ml-24">
      sidebar goes here
    </div>
    <div class="w-full">
      <router-view />

    </div>
  </div>
</template>

<style src="./css/main.css">
</style>
