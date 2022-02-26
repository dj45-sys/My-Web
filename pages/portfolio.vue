<template>
  <div>
    <Navbar name="Knowledge" name1="Featured Projects" id="Portfolio" />
    <Sidebar />
    <Knowledge />
    <Prtfolio />
  </div>
</template>

<script>
export default {
  name: "Portfolio",
  head() {
    return {
      title: "Portfolio - Juan Esteban | Dj45-SyS",
    };
  },
};
</script>