<template>
  <div
    id="Aboutme"
    class="h-100vh bg-gray-200 flex justify-center items-center"
  >
    <img
      class="flex self-center w-1/2 overflow-hidden"
      src="../static/SVG/Code.svg"
      alt="Code"
    />
    <div class="flex-col px-10">
      <h1 class="font-roboto font-semibold mb-7 text-3xl">Let me tell you something about me</h1>
      <p class=" font-light leading-10">
        I'm A Nerd And An Average Developer From Colombia, I'm 15 Years Old, My
        Hobbies Are Programming And Video Games. <br/> I'm just a average
        programmer that have skills in the area of web and desktop
        development
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>
<style>
.h-100vh {
  height: 100vh;
}
</style>
