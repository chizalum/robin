<template>
  <div class="top">
      <div class="robincontainer">
        <img src="@/assets/robin.png" alt="logo" class="robin">
      </div>
      <div class="routes">
        <router-link to="/" class="home1">Pricing</router-link> 
        <router-link to="/" class="home">Docs</router-link>
        <router-link to="/" class="home">Use Cases</router-link>
        <router-link to="/" class="home">SDKs</router-link>
        <router-link to="/" class="home">Enterprise</router-link>
        <router-link to="/" class="home">Try Demo</router-link>
      </div>
      <div class="routes2">
        <router-link to="/" class="home2">Sign In</router-link> 
        <router-link to="/" class="get">
          <span to="/" class="gettext">Get Started</span>
        </router-link>
      </div>
  </div>
</template>

<script>
export default {
  props: ['Navbar']
}
</script>