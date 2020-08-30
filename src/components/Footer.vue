<template>
  <footer class="footer has-background-dark has-pattern">
    <div class="container has-text-centered has-text-grey-lighter">
      <div class="buttons is-centered">
        <a class="button is-primary is-medium" href="mailto:marco@pagani.io">
          <font-awesome class="icon" :icon="['far', 'envelope']" />
        </a>
        <a
          class="button is-primary is-medium"
          href="https://www.linkedin.com/in/marco-pagani/"
        >
          <font-awesome class="icon" :icon="['fab', 'linkedin']" />
        </a>
        <a
          class="button is-primary is-medium"
          href="https://github.com/Marco-Pagani"
        >
          <font-awesome class="icon" :icon="['fab', 'github']" />
        </a>
        <a
          class="button is-primary is-medium"
          href="https://www.instagram.com/paganorama/?hl=en"
        >
          <font-awesome class="icon" :icon="['fab', 'instagram']" />
        </a>
      </div>
      <p class="is-size-6">
        This site was coded by Marco Pagani, using
        <a class="has-text-primary" href="https://bulma.io">Bulma</a>.<br />
        The source code is licensed
        <a
          class="has-text-primary"
          href="http://opensource.org/licenses/mit-license.php"
          >MIT</a
        >, I hope it helps someone ♡<br />
        v2.0.0
      </p>
    </div>
  </footer>
</template>

<style scoped>
.has-pattern {
  background: #363636 url("~@/assets/images/prism.png");
}
</style>