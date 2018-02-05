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
@import url('https://fonts.googleapis.com/css?family=Abril+Fatface|Bitter|Open+Sans|Playfair+Display');
/* @import url('https://fonts.googleapis.com/css?family=Bitter|Lobster|Lobster+Two|Open+Sans|Playfair+Display'); */
ul {
  list-style-type: none;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: rgb(54, 154, 221);
}
</style>
