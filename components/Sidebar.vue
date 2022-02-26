<template>
  <div
    class="
      fixed
      top-1/2
      w-16
      h-32
      rounded-3xl
      shadow-2xl
      opacity-75
      bg-gray-300
      flex
      justify-center
      items-center
      flex-col
      left-3
      backdrop-blur-xl
    "
  >
    <router-link to="/" class="cursor-pointer" >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-5 w-5"
        viewBox="0 0 20 20"
        fill="currentColor"
      >
        <path
          d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z"
        />
      </svg>
    </router-link>
    <router-link to="/portfolio" class="cursor-pointer">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-6 w-6"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
        />
      </svg>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "SideBar",
};
</script>

<style>
</style>