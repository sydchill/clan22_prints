<template>
  <div id="navigation">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item">
            <NuxtLink to="/">
              <h1 class="title secondary-font primary-color mr-5">CLAN 22</h1>
            </NuxtLink>
          </a>
          <span
            class="navbar-burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarMenuHeroA"
            @click="isActive = !isActive"
            :class="isActive ? 'is-active' : ''"
          >
            <span></span>
            <span></span>
            <span></span>
          </span>
        </div>
        <div
          id="navbarMenuHeroA"
          :class="isActive ? 'is-active' : ''"
          class="navbar-menu"
        >
          <div class="navbar-start ml-1">
            <NuxtLink to="how-it-works" class="navbar-item primary-color">
              Create
            </NuxtLink>
       
            <a class="navbar-item primary-color"> Contact </a>
          </div>
          <div class="navbar-end">
            <div class="buttons ml-1">
              <a
                href="https://www.instagram.com/clan22_designs/"
                target="_blank"
                class="navbar-item primary-color"
              >
                <i class="fa fa-instagram"></i>
              </a>
              <a
                href="https://www.facebook.com/Clan-22-designs-102318355616008/shop/"
                target="_blank"
                class="navbar-item primary-color"
              >
                <i class="fa fa-facebook"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>


<script>
export default {
  data() {
    return {
      isActive: false,
    };
  },
};
</script>