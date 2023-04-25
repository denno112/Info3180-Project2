<script setup>
import { ref } from "vue";

</script>

<template>
    <div class="container">
      <div class=" picture">
        <img src="pictures\Homepagepic.jpg" alt="">
      </div>
      <div class="home">
        <!-- <img src="pictures\camera icon.jpg" alt=""> -->
        <h1>Photogram</h1>
        <p>Share photos of your favourite moments with frineds, family and the world.</p>
      <div class="button-container">
        <router-link to="/register">
          <button class="register"> Register</button>
        </router-link>
        <router-link to="/login">
          <button class="login">Login</button>
        </router-link>
    
        
        
      </div>
      </div>
    </div>
</template>

<style>
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.picture, .home {
  width: 300px;
  height: 200px;
  background-color: #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
}
.picture img {
  max-width: 100%;
  max-height: 100%;
}

.text-box {
  background-color: #fff;
}
.btn-container button {
  padding: 10px 20px;
  background-color: #555;
  color: #fff;
  border: none;
  border-radius: 5px;
  margin: 0 5px;
}

.register, .login {
  padding: 10px 20px;
  background-color: #555;
  color: #fff;
  border: none;
  border-radius: 5px;
}

.register {
  background-color: green;
  margin-right: 10px;
}

.login {
  background-color: blue;
  margin-left: 10px;
}

/* Add any component specific styles here */
</style>