<template>
  <div>
    <svg width="117" height="130"><defs id="SvgjsDefs1152"></defs><g id="main_text" rel="mainfill" name="main_text" feature="main_text" xmlns:name="mainText_mainfill" groupname="main_text" fill="#fff" transform="translate(60, 130) scale(3.5381535038932146)"><path d=""></path></g><g id="SvgjsG1154" rel="mainfill" name="symbol" feature="symbol" xmlns:name="symbol_mainfill" fill="#fff" transform="translate(2.5538740157480313, 2.5538740157480313) scale(0.22306299212598427)"><g><path d="M124.9,174.1C79.7,174.1,43,210.8,43,256c0,4.5,3.7,8.2,8.2,8.2s8.2-3.7,8.2-8.2c0-36.1,29.4-65.5,65.5-65.5   c4.5,0,8.2-3.7,8.2-8.2C133.1,177.7,129.4,174.1,124.9,174.1z"></path><path d="M428.1,124.9c22.6,0,41-18.4,41-41s-18.4-41-41-41s-41,18.4-41,41S405.5,124.9,428.1,124.9z M428.1,59.4   c13.6,0,24.6,11,24.6,24.6s-11,24.6-24.6,24.6s-24.6-11-24.6-24.6S414.5,59.4,428.1,59.4z"></path><path d="M428.1,387.1c-22.6,0-41,18.4-41,41s18.4,41,41,41s41-18.4,41-41S450.7,387.1,428.1,387.1z M428.1,452.6   c-13.6,0-24.6-11-24.6-24.6s11-24.6,24.6-24.6s24.6,11,24.6,24.6S441.6,452.6,428.1,452.6z"></path><path d="M428.1,346.1c-27.5,0-51.9,13.7-66.8,34.6l-125.8-71.4c7.8-16.2,12.3-34.2,12.3-53.3c0-19.1-4.5-37.2-12.3-53.3l125.8-71.4   c14.9,20.9,39.2,34.6,66.8,34.6c45.2,0,81.9-36.8,81.9-81.9S473.2,2,428.1,2s-81.9,36.8-81.9,81.9c0,11.8,2.5,23,7,33.1   l-125.7,71.4c-22-33.3-59.7-55.3-102.5-55.3C57.1,133.1,2,188.2,2,256s55.1,122.9,122.9,122.9c42.8,0,80.5-22,102.5-55.3L353.2,395   c-4.5,10.1-7,21.3-7,33.1c0,45.2,36.8,81.9,81.9,81.9s81.9-36.8,81.9-81.9S473.2,346.1,428.1,346.1z M428.1,18.4   c36.1,0,65.5,29.4,65.5,65.5s-29.4,65.5-65.5,65.5s-65.5-29.4-65.5-65.5S391.9,18.4,428.1,18.4z M124.9,362.5   c-58.7,0-106.5-47.8-106.5-106.5s47.8-106.5,106.5-106.5S231.4,197.3,231.4,256S183.6,362.5,124.9,362.5z M428.1,493.6   c-36.1,0-65.5-29.4-65.5-65.5s29.4-65.5,65.5-65.5s65.5,29.4,65.5,65.5S464.2,493.6,428.1,493.6z"></path><rect x="297.2" y="247.8" width="16.2" height="16.4"></rect><rect x="329.8" y="247.8" width="16.2" height="16.4"></rect><rect x="362.5" y="247.8" width="16.2" height="16.4"></rect></g></g></svg>
    <ul>
      <li v-for="(n, index) in testys" :key="index" >
        <h1 :class="'title title' + n">Athenium</h1>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  computed: {
    testys() {
      return 22;
    }
  }
}
</script>

<style>
ul {
  margin-bottom: 25px;
}
svg {
  /* display: none; */
  transform: rotate(90deg);
}
.title {
  display: block;
  font-family: "Abril Fatface", serif;
  font-weight: 300;
  font-size: 100px;
  color: #fff;
  letter-spacing: 0px;
  margin-top: -30px;
}
.title:not(.title1) {
  display: none;
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

.links {
  padding-top: 15px;
}
</style>
