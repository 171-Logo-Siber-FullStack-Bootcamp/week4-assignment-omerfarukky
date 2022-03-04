<template>
  <div id="wrapper">
    <SidebarComponents />
    <NavbarComponents />
  </div>
</template>

<script>
import SidebarComponents from "./components/SidebarComponents.vue";
import NavbarComponents from "./components/NavbarComponents.vue";

export default {
  name: "App",
  components: {
    SidebarComponents,
    NavbarComponents,
  },
};
</script>

<style>
@import "./assets/css/sb-admin-2.css";
@import "./assets/css/sb-admin-2.min.css";
</style>

