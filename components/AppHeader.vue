<template>
  <header class="app-header">
      <h1 class="title">
          Athenium.io
      </h1>
      <nav>
          <ul>
            <li v-for="(item, index) in urls">
                {{item.text}}
            </li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    data () {
        return { 
            urls: [
                { text: "Home", url: "#"},
                { text: "Notes", url: "#"},
                { text: "Bookmarks", url: "#"},
                { text: "Alarms", url: "#"},
                { text: "Memoes", url: "#"}
            ]
        }
    }
}
</script>

<style>
    .app-header {
        /* border-bottom: 1px solid #333; */
    }
    .app-header h1 {
        border-bottom: 1px solid #333;
        text-align: center;
    }
    .app-header nav {
        border-bottom: 1px solid #aaa;
        padding: 10px;
    }
    /* nav {
        display: none;
    }
    .app-header:hover nav {
        display: block;
    } */
    .app-header ul {
        text-align: center;
    }
    .app-header li {
        color: #333;
        margin-left: 20px;
        text-align: center;
    }
</style>
