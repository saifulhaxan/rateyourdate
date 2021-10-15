<template>
  <header class="header-global">
    <base-nav class="navbar-main" white type="" effect="light" expand>
      <div class="d-flex rounded-3 shadow justify-content-end p-3 w-100">
        <div class="profile-info">
          <a href="" class="position-relative px-3"
            ><i class="fa fa-bell text-danger" aria-hidden="true"></i
            ><span class="count">3</span></a
          >
          <base-dropdown tag="li" class="nav-item">
            <a
              slot="title"
              href="#"
              class="nav-link text-dark"
              data-toggle="dropdown"
              role="button"
            >
              <i class="fa fa-user text-danger pr-2"></i>
              <span class="nav-link-inner--text pr-2">Hi, Mark</span>
              <i class="fa fa-chevron-down text-danger"></i>
            </a>
            <router-link to="/landing" class="dropdown-item"
              >Landing</router-link
            >
            <router-link to="/profile" class="dropdown-item"
              >Profile</router-link
            >
            <router-link to="/login" class="dropdown-item">Login</router-link>
            <router-link to="/register" class="dropdown-item"
              >Register</router-link
            >
          </base-dropdown>
        </div>
      </div>
      <div class="row" slot="content-header" slot-scope="{ closeMenu }">
        <div class="col-6 collapse-brand">
          <a
            href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
          >
            <img src="img/brand/blue.png" />
          </a>
        </div>
        <div class="col-6 collapse-close">
          <close-button @click="closeMenu"></close-button>
        </div>
      </div>
    </base-nav>
  </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown,
  },
};
</script>
<style>
</style>
