<template>
  <ul
    class="navbar-nav bg-gradient-primary sidebar sidebar-dark accordion"
    id="accordionSidebar"
  >
    <SidebarBrand />
    <SidebarInterface />
    <SidebarAddons />
    <SidebarMessage />
  </ul>
</template>

<script>
import SidebarBrand from "./Sidebar/SidebarBrand.vue";
import SidebarInterface from "./Sidebar/SidebarInterface.vue";
import SidebarAddons from "./Sidebar/SidebarAddons.vue";
import SidebarMessage from "./Sidebar/SidebarMessage.vue";

export default {
  name: "SidebarComponents",
  components: {
    SidebarBrand,
    SidebarInterface,
    SidebarAddons,
    SidebarMessage,
  },
};
</script>