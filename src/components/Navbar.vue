<template>
  <nav
    class="navbar is-spaced is-primary"
    id="coloredNav"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="navbar-brand">
      <g-link id="logo" class="navbar-item logo" to="/">
        <g-image
          id="logo-img"
          alt="Marco Pagani logo"
          src="~/assets/images/logo/logo_square250.png"
        />
      </g-link>

      <a
        role="button"
        class="navbar-burger burger"
        :class="{ 'is-active': active }"
        aria-label="menu"
        aria-expanded="false"
        data-target="myNavbar"
        @click="active = !active"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="myNavbar" class="navbar-menu" :class="{ 'is-active': active }">
      <div class="navbar-start"></div>

      <div class="navbar-end">
        <g-link class="navbar-item" to="/">Home</g-link>
        <g-link class="navbar-item" to="/projects">Projects</g-link>
        <g-link class="navbar-item" to="/about">About</g-link>

        <div class="navbar-item">
          <a
            class="button is-primary is-inverted is-outlined"
            href="mailto:marco.pagani109@gmail.com"
          >
            <strong>Contact Me!</strong>
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      active: false,
    };
  },
};
</script>

<style scoped>
#logo {
  padding: 0%;
  max-height: 3.25rem;
  max-width: 3.25rem;
  padding: 1px;
  border: 2px solid #021a40;
}
</style>