<template>
  <section class="container">
    <div>
      <p>Register Page</p>
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
ul {
  list-style-type: none;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: #fff;
}
.pageTitle {
  font-family: 'Playfair Display', serif;
  color: rgb(87, 87, 87);
  font-size: 36px;
  margin-bottom: 20px;
}

p, a, button, input, .submitBtn {
  color: rgb(75, 75, 75);
  font-family: 'Open Sans', 'Bitter', 'Helvetica Neue', 'Helvetica', sans-serif;
  font-size: 18px;
  letter-spacing: -1px;
}
</style>
