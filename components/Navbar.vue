<template>
  <div
    class="
      fixed
      top-3
      left-3
      z-40
      w-64
      h-16
      backdrop-blur-xl
      flex flex-row
      justify-center
      items-center
      shadow-2xl
      bg-gray-200
      opacity-80
      rounded-3xl
    "
  >
    <a v-on:click="this.scrollToTop" class="cursor-pointer">{{name}}</a>
    <pre> | </pre>
    <a v-on:click="this.scrollToAboutMe" class="cursor-pointer">{{name1}}</a>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props:['name','name1','id'],
  methods: {
    scrollToTop: function () {
      window.scrollTo({ top: 0, left: 0, behavior: "smooth" });
    },
    scrollToAboutMe: function () {
      const abm = document.getElementById(this.id).offsetTop;
      window.scrollTo({ top: abm, left: 0, behavior: "smooth" });
    },
  },
};
</script>

<style>
</style>