<template>
  <section class="container">
    <div>
      <!-- <app-logo/> -->
      <ul>
        <li v-for="(n, index) in testys" :key="index" >
          <h1 :class="'title title' + n">Athenium</h1>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  computed: {
    testys() {
      return 31;
    }
  },
  components: {
    AppLogo
  }
}
let boo = 'b';
</script>

<style>
ul {
  list-style-type: none;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
.title1 {
  font-family: 'Abril Fatface', cursive !important;
}
.title2 {
font-family: 'Alegreya', serif;
}
.title3 {
font-family: 'Alfa Slab One', cursive;
}
.title4 {
font-family: 'Amatic SC', cursive;
}
.title5 {
font-family: 'Bitter', serif;
}
.title6 {
font-family: 'Boogaloo', cursive;
}
.title7 {
font-family: 'Bree Serif', serif;
}
.title8 {
font-family: 'Cardo', serif;
}
.title9 {
font-family: 'Cinzel', serif;
}
.title10 {
font-family: 'Comfortaa', cursive;
}
.title11 {
font-family: 'Cormorant Garamond', serif;
}
.title12 {
font-family: 'Crimson Text', serif;
}
.title13 {
font-family: 'Inconsolata', monospace;
}
.title14 {
font-family: 'Josefin Slab', serif;
}
.title15 {
font-family: 'Lobster', cursive;
}
.title16 {
font-family: 'Merriweather', serif;
}
.title17 {
font-family: 'Noticia Text', serif;
}
.title18 {
font-family: 'Open Sans', sans-serif;
}
.title19 {
font-family: 'PT Serif', serif;
}
.title20 {
font-family: 'Playfair Display', serif;
}
.title21 {
font-family: 'Playfair Display SC', serif;
}
.title22 {
font-family: 'Poiret One', cursive;
}
.title23 {
font-family: 'Quattrocento', serif;
}
.title24 {
font-family: 'Rammetto One', cursive;
}
.title25 {
font-family: 'Roboto Mono', monospace;
}
.title26 {
font-family: 'Roboto Slab', serif;
}
.title27 {
font-family: 'Rokkitt', serif;
}
.title28 {
font-family: 'Slabo 27px', serif;
}
.title29 {
font-family: 'Source Code Pro', monospace;
}
.title30 {
font-family: 'Tinos', serif;
}
.title31 {
font-family: 'Vollkorn', serif;
}
</style>
