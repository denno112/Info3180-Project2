<template>
  <form>
    <h3>Register</h3>

    <label>Username</label>
    <input type="username" required v-model="username" />

    <label>Password</label>
    <input type="password" required v-model="password" />

    <label>Firstname</label>
    <input type="firstname" required v-model="firstname" />

    <label>Lastname</label>
    <input type="lastname" required v-model="lastname" />

    <label>Email</label>
    <input type="email" required v-model="email" />

    <label>Location</label>
    <input type="location" required v-model="location" />

    <label>Biography</label>
    <input type="biography" required v-model="biography" />

    <label>Photo</label>
    <input type="file" @change="onFileSelected" />

    <div class="submit">
      <button type="submit">Register</button>
    </div>
  </form>
</template>

