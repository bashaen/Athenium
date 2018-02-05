<template>
  <section class="container">
    <div>
      <app-logo/>
      <login-form></login-form>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import LoginForm from '~/components/LoginFormSmall.vue'

export default {
  components: {
    AppLogo,
    LoginForm
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Abril+Fatface|Alegreya|Alegreya+Sans|Bitter|Boogaloo|Bree+Serif|Cinzel|Cinzel+Decorative|Comfortaa|Inconsolata|Josefin+Sans|Josefin+Slab|Lobster|Lobster+Two|Open+Sans|Open+Sans+Condensed:300|Playfair+Display|Playfair+Display+SC|Poiret+One|Ramaraja|Rammetto+One|Tenali+Ramakrishna');
ul {
  list-style-type: none;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: rgb(102, 165, 207);
}
</style>
