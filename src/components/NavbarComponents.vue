<template>
  <div id="content-wrapper" class="d-flex flex-column">
    <!-- Main Content -->
    <div id="content">
      <nav
        class="
          navbar navbar-expand navbar-light
          bg-white
          topbar
          mb-4
          static-top
          shadow
        "
      >
        <NavbarSearch />
        <ul class="navbar-nav ml-auto">
          <NavbarAlerts />
          <NavbarMessage />
          <NavbarLogin />
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
import NavbarSearch from "./Navbar/NavbarSearch.vue";
import NavbarAlerts from "./Navbar/NavbarAlerts.vue";
import NavbarMessage from "./Navbar/NavbarMessage.vue";
import NavbarLogin from "./Navbar/NavbarLogin.vue";

export default {
  name: "NavbarComponents",
  components: {
    NavbarSearch,
    NavbarAlerts,
    NavbarMessage,
    NavbarLogin,
  },
};
</script>