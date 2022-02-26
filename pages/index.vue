<template>
  <div>
    <Navbar name="Home" name1="About Me" id="Aboutme" />
    <Sidebar />
    <Cover />
    <Phrase />
    <AboutMe />
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  head() {
    return {
      title: "Home - Juan Esteban | Dj45-SyS",
    };
  },
};
</script>
