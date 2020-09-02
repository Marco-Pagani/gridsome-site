<template>
  <Layout>
    <Hero />
    <section class="section is-narrow">
      <div class="container">
        <div class="columns">
          <div class="column is-half">
            <h2 class="title is-3">Here's the basics</h2>
            <p class="is-size-5">
              I'm a software developer based in Miami, Florida with a creative
              eye and a passion for programming. I know that software
              development is more about solving problems than writing code (but
              I'm pretty good at that too). I know how to work with my team to
              create solutions for our users.
            </p>
          </div>
          <div class="column is-half">
            <figure class="image is-128x128">
              <img src="https://bulma.io/images/placeholders/128x128.png" />
            </figure>
          </div>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
import Hero from "~/components/Hero.vue";
export default {
  components: {
    Hero,
  },
  metaInfo: {
    title: "Marco Pagani",
  },
};
</script>

<style>
.container {
  max-width: 1200px;
}
</style>
