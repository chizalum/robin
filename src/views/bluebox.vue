<template>
  <div class="bluebox">
    <div class="widthcontrol">
      <div class="firstcolumn"> 
        <div class="firstone">
          <h2 class="ready">Ready to have a chat?</h2>
          <p class="love">We'd love to talk about your messaging strategy and help make your software more conversational.</p>
        </div>
        <div class="secondone">
          <router-link to="/" class="talkbtn">
            <span class="talkrbn">Talk To Sales</span>
            <img src="@/assets/whitearrow.png" alt="arrow" class="whitearrow">
          </router-link>
        <router-link to="/" class="trybtn">
          <span class="tryrbn">Try Robin</span>
          <img src="@/assets/whitearrow.png" alt="arrow" class="whitearrow1">
        </router-link>
      </div>
    </div>
    <hr class="bluerule">
    <div class="lastflex">
      <div class="rob">
        <img src="@/assets/robin1.png" alt="arrow" class="robin1">
      </div>
      <div class="robdets">
        <div class="robdets1">
          <router-link to="/" class="robtext1">Resources</router-link>
          <router-link to="/" class="robtext">Documentation</router-link>
          <router-link to="/" class="robtext">Developer API</router-link>
          <router-link to="/" class="robtext">Product Demos</router-link>
          <router-link to="/" class="robtext">Help Center</router-link>
          <router-link to="/" class="robtext">System Status</router-link>
        </div>
        <div class="robdets2">
          <router-link to="/" class="robtext1">Company</router-link>
          <router-link to="/" class="robtext">About</router-link>
          <router-link to="/" class="robtext">Security & Privacy</router-link>
          <router-link to="/" class="robtext">Blog</router-link>
        </div>
      </div>
    </div>
    <hr class="lastrule">
    <div class="specialflex">
      <div class="specialcontainer1">
        <router-link to="/" class="specialtext1">© 2021 Robin Inc.</router-link>
      </div>
      <div class="specialcontainer2">
        <router-link to="/" class="specialtext">Terms of Service</router-link>
        <router-link to="/" class="specialtext">Privacy Policy</router-link>
        <router-link to="/" class="specialtext">Cookie Settings</router-link>
        <router-link to="/" class="specialtext4">Sub-Processors</router-link>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  props: ['bluebox']
}
</script>