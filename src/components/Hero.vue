<template>
  <section class="section has-hero-image" id="home">
    <div class="columns">
      <div class="column is-5-fullhd is-6-widescreen is-7-desktop pt-5">
        <h1 class="title is-size-1 has-text-weight-bold has-text-black">
          Hi, I’m <mark>Marco Pagani</mark>. I’m a software developer and a
          designer.
        </h1>
        <h2 class="is-size-3 pr-4">
          I have a creative eye and a passion for programming. I know that
          software development is more about solving problems than writing code
          (but I'm pretty good at that too).
        </h2>
      </div>
    </div>
    <p id="hero-footer">
      <a>Resume</a>
      <a>Resume</a>
      <a>Resume</a>
    </p>
  </section>
</template>

<script>
export default {
  metaInfo: {
    link: [
      {
        rel: "stylesheet",
        href:
          "https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap",
      },
    ],
  },
};
</script>

<style lang="scss" scoped>
@import "~bulma/sass/utilities/_all.sass";

@include desktop {
  .has-hero-image {
    background: #f2f2f2 url("~@/assets/images/hero/hero_image_comp.png") right;
    background-repeat: no-repeat;
    background-size: 2vw;
  }
}
h2 {
  line-height: 1.1em;
}
mark {
  display: inline-block;
  padding: 0em;
  background-color: #fcc335;
}
.section {
  padding-bottom: 1rem;
}
#hero-footer {
  padding-top: 2rem;
}
.blinking-cursor {
  font-weight: 100;
  font-size: 3rem;
  color: #f2f2f3;
  -webkit-animation: 1s blink step-end infinite;
  -moz-animation: 1s blink step-end infinite;
  -ms-animation: 1s blink step-end infinite;
  -o-animation: 1s blink step-end infinite;
  animation: 1s blink step-end infinite;
}

@keyframes Blink {
  from,
  to {
    color: transparent;
  }
  50% {
    color: #f2f2f3;
  }
}

@-moz-keyframes blink {
  from,
  to {
    color: transparent;
  }
  50% {
    color: #f2f2f3;
  }
}

@-webkit-keyframes blink {
  from,
  to {
    color: transparent;
  }
  50% {
    color: #f2f2f3;
  }
}

@-ms-keyframes blink {
  from,
  to {
    color: transparent;
  }
  50% {
    color: #f2f2f3;
  }
}

@-o-keyframes blink {
  from,
  to {
    color: transparent;
  }
  50% {
    color: #f2f2f3;
  }
}
</style>