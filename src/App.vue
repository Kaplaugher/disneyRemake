<template>
  <div
    id="app"
    class="flex bg-gray-900 text-white min-h-screen"
  >
    <div class="nav w-24 fixed min-h-screen text-gray-500 flex justify-center items-center">
      <ul>
        <li class="mb-10">
          <a
            href="http://"
            target="_blank"
            rel="noopener noreferrer"
            class="hover:text-white"
          >Hi
          </a>
        </li>
        <li class="mb-10">
          <a
            href="http://"
            target="_blank"
            rel="noopener noreferrer"
            class="hover:text-white"
          >Hi
          </a>
        </li>
        <li class="mb-10">
          <a
            href="http://"
            target="_blank"
            rel="noopener noreferrer"
            class="hover:text-white"
          >Hi
          </a>
        </li>
        <li class="mb-10">
          <a
            href="http://"
            target="_blank"
            rel="noopener noreferrer"
            class="hover:text-white"
          >Hi
          </a>
        </li>

      </ul>
    </div>
    <div class="w-full ml-24">
      <div class="container mx-auto">
        <router-view />
      </div>
    </div>
  </div>
</template>

<style src="./css/main.css">
</style>
