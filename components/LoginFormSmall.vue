<template>
  <div>
      <form class="LoginFormSmall">
        <input type="text" class="username" placeholder="Username">
        <input type="text" class="password" placeholder="Password">
        <button class="submitBtn">Submit</button>
    </form>
    <p>Don't have an account?  <a href="#">Register Now</a></p>
  </div>
</template>

<style>
    .LoginFormSmall {
        clear: both;
        display: block;
        width: 100%
    }
    input {
        display: block;
        width: 100%;
        margin: 0 auto 15px auto;
        border: 1px solid black;
        border-color: rgb(245, 142, 245);
        padding: 8px;
    }
    .submitBtn {
        background: rgb(54, 115, 221);
        /* border: 1px solid rgb(255, 184, 255); */
        border: none;
        width: 100%;
        padding: 8px;
        color: #fff;
        font-weight: bold;
        font-family: 'Helvetica Neue', Helvetica, sans-serif;
        margin-bottom: 20px;
        margin-top: 20px;
    }
    p, a {
        color: #fff;
    }
</style>
