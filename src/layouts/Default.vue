<template>
  <div>
    <Navbar />
    <slot />
    <Footer />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import Navbar from "~/components/Navbar.vue";
import Footer from "~/components/Footer.vue";
export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
  line-height: 1.5;
  min-height: 100vh;
}
</style>
