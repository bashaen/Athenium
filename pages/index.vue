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
      return 15;
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
font-family: 'Bitter', serif;
}
.title4 {
font-family: 'Boogaloo', cursive;
}
.title5 {
font-family: 'Bree Serif', serif;
}
.title6 {
font-family: 'Cinzel', serif;
}
.title7 {
font-family: 'Comfortaa', cursive;
}
.title8 {
font-family: 'Inconsolata', monospace;
}
.title9 {
font-family: 'Josefin Slab', serif;
}
.title10 {
font-family: 'Lobster', cursive;
}
.title11 {
font-family: 'Open Sans', sans-serif;
}
.title12 {
font-family: 'Playfair Display', serif;
}
.title13 {
font-family: 'Playfair Display SC', serif;
}
.title14 {
font-family: 'Poiret One', cursive;
}
.title15 {
font-family: 'Rammetto One', cursive;
}
</style>
