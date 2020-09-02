<template>
  <section class="hero is-medium has-hero-image" id="home">
    <div class="hero-body">
      <div class="container">
        <h1 class="title is-size-1 has-text-white">
          Hi, I'm <span class="has-text-primary">Marco Pagani</span>. I'm a
          software developer and a designer.<span class="blinking-cursor"
            >|</span
          >
        </h1>
        <a href="#summary" class="button is-warning is-medium">Check me out</a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.title {
  font-family: "Rubik", sans-serif;
}
.has-hero-image {
  background: #6095cb url("~@/assets/images/hero_2560_flip.jpg") center center;
  background-size: cover;
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