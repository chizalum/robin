<template>

<Navbar></Navbar>

  <div class="firstdiv">
    <h1 class="simple">Simple & Transparent Pricing. No surprises.</h1>
    <h3 class='the'>The only tool you will need to power conversations. </h3>
    <router-link to="/" class="btn1">
    <span class="starter">Start Free Trial</span>
    <img src="@/assets/Arrow.png" alt="arrow image" class="ticker">
    </router-link>
  </div>

  <pricingcard></pricingcard>

  <p class="trust">Trusted by experts at</p>
  <img src="@/assets/screenshot.png" alt="brand logos" class="screenshot">
  <div class="dropcontainer">
    <h3 class="common">Commonly asked questions</h3>
    <p class="ship">Ship in-app chat messaging with all the features your users expect.</p>
    <div class="droplayer">
      <div class="dropcontent dropcontent1" @click="toggle1">
        <p class="droptext">How is MAU calculated?</p>
        <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available1:available1}">
      </div>
      <div class="droppingsblock" v-if="active1">
        <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
      </div>
      </div>
    <div class="droplayer">
     <div class="dropcontent" @click="toggle2">
        <p class="droptext">What is the difference between Starter, Pro, and Enterprise plans?</p>
        <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available2:available2}">
      </div>
      <div class="droppingsblock" v-if="active2" >
        <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
      </div>
    </div>
    <div class="droplayer">
      <div class="dropcontent" @click="toggle3">
        <p class="droptext">What happens if I hit my MAU limit?</p>
        <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available3:available3}">
      </div>
      <div class="droppingsblock" v-if="active3">
        <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
      </div>
   </div>
   <div class="droplayer">
     <div class="dropcontent" @click="toggle4">
       <p class="droptext">How do I purchase higher levels of support?</p>
       <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available4:available4}">
     </div>
      <div class="droppingsblock" v-if="active4">
        <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
      </div>
   </div>
   <div class="droplayer">
     <div class="dropcontent" @click="toggle5">
        <p class="droptext">What other limits do I need to be aware of?</p>
        <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available5:available5}">
     </div>
     <div class="droppingsblock" v-if="active5">
        <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
      </div>
    </div>
    <div class="droplayer">
      <div class="dropcontent" @click="toggle6">
        <p class="droptext">Is every feature automatically included in the enterprise plan?</p>
        <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available6:available6}">
     </div>
     <div class="droppingsblock" v-if="active6">
       <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
     </div>
   </div>
   <div class="droplayer">
    <div class="dropcontent" @click="toggle">
      <p class="droptext">Do the prices listed on the pricing page include tax?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available:available}">
     </div>
     <div class="droppingsblock" v-if="active">
       <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
     </div>
    </div>
    <p class="got">Got additional questions?</p>
    <p class="we">We would love to have a chat with you.</p>
    <router-link to="/" class="reach">
      <span to="/" class="contact">Contact Support</span> 
      <img src="@/assets/bluearrow.png" alt="arrow" class="bluearrow">
    </router-link>
  </div>
  <chatscreen></chatscreen>
  <bluebox></bluebox>
</template>

<script>
import Navbar from './Navbar.vue'
import bluebox from './bluebox.vue'
import pricingcard from './pricingcard.vue'
import chatscreen from './chatscreen.vue'
export default {
  name: 'HomeView',
  components: {
    Navbar: Navbar,
    bluebox: bluebox,
    pricingcard: pricingcard,
    chatscreen: chatscreen,
  },
  data(){
    return {
    available: false,
    available1: false,
    available3: false,
    available4: false,
    available5: false,
    available6: false,
    active: false,
    active1: false,
    active2: false,
    active3: false,
    active4: false,
    active5: false,
    active6: false
    }
  },
  methods: {
      toggle () {
        this.active = !this.active;
        this.available = !this.available
      },
      toggle1 () {
        this.active1 = !this.active1;
        this.available1 = !this.available1
      },
      toggle2 () {
        this.active2 = !this.active2;
        this.available2 = !this.available2
      },
      toggle3 () {
        this.active3 = !this.active3;
        this.available3 = !this.available3
      },
      toggle4 () {
        this.active4 = !this.active4;
        this.available4 = !this.available4
      },
      toggle5 () {
        this.active5 = !this.active5;
        this.available5 = !this.available5
      },
      toggle6 () {
        this.active6 = !this.active6;
        this.available6 = !this.available6
      }
    }
}
</script>
