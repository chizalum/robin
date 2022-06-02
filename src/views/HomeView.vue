<template>
  <div class="top">
      <div class="robincontainer">
        <img src="@/assets/robin.png" alt="logo" id="robin">
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
        <button id="get">
          <router-link to="/" id="gettext">Get Started</router-link>
        </button>
      </div>
  </div>
  <div class="firstdiv">
    <h1 id="simple">Simple & Transparent Pricing. No surprises.</h1>
    <h3 id='the'>The only tool you will need to power conversations. </h3>
    <button id="btn1">
    <router-link to="/" id="starter">Start Free Trial</router-link>
    <img src="@/assets/Arrow.png" alt="arrow image" id="ticker">
    </button>
  </div>
  <div class="boxes">
    <div id="box1">
        <p class="maroon">Starter</p>
        <p class="dollars">$69/mo</p>
        <hr class="single">
        <div class="features">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle">
          <p class="core">Core Chat Features</p>
        </div>
        <div class="features1">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle1">
          <p class="core1"> <span class="opaque">10,000 </span>Monthly Active Users</p>
        </div>
        <div class="features2">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle2">
          <p class="core2">MAU Overage Rate</p>
        </div>
        <div class="features3">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle3">
          <p class="core3"><span class="opaque">100 </span>Concurrent Included</p>
        </div>
        <div class="features4">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle4">
          <p class="core4">Limited Message Storage</p>
        </div>
        <hr class="double">
        <div class="last">
          <router-link to="/" class="lasttext">Get Started</router-link>
          <img src="@/assets/lastarrow.png" alt="arrow image" class="lastarrow">
        </div>
    </div>
    <div id="box2">
      <p class="maroon">Growth</p>
      <p class="dollars">$389/mo</p>
      <hr class="single">
        <div class="features">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle">
          <p class="core">Core Chat Features</p>
        </div>
        <div class="features1">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle1">
          <p class="core1"><span class="opaque">25,000 </span>Monthly Active Users</p>
        </div>
        <div class="features2">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle2">
          <p class="core2">MAU Overage Rate</p>
          </div>
        <div class="features3">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle3">
          <p class="core3"><span class="opaque">100 </span>Concurrent Included</p>
        </div>
        <div class="features4">
            <img src="@/assets/circlecheck.png" alt="arrow image" class="circle4">
            <p class="core4">Limited Message Storage</p>
        </div>
        <hr class="double">
        <div class="last">
          <router-link to="/" class="lasttext">Get Started</router-link>
          <img src="@/assets/lastarrow.png" alt="arrow image" class="lastarrow">
        </div>
    </div>
    <div id="box3">
      <p class="maroon">Pro</p>
      <p class="dollars">$799/mo</p>
      <hr class="single">
        <div class="features">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle">
          <p class="core">Core Chat Features</p>
        </div>
        <div class="features1">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle1">
          <p class="core1"><span class="opaque">50,000 </span>Monthly Active Users</p>
        </div>
        <div class="features2">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle2">
          <p class="core2">MAU Overage Rate</p>
        </div>
        <div class="features3">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle3">
          <p class="core3"><span class="opaque">100 </span>Concurrent Included</p>
        </div>
        <div class="features4">
            <img src="@/assets/circlecheck.png" alt="arrow image" class="circle4">
            <p class="core4">Limited Message Storage</p>
        </div>
        <hr class="double">
        <div class="last">
          <router-link to="/" class="lasttext">Get Started</router-link>
          <img src="@/assets/lastarrow.png" alt="arrow image" class="lastarrow">
        </div>
    </div>
    <div id="box4">
      <p class="maroon">Enterprise</p>
      <p class="dollars">Customized</p>
      <hr class="single">
        <div class="features">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle">
          <p class="core">Core Chat Features</p>
        </div>
        <div class="features1">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle1">
          <p class="core1"><span class="opaque">100,000+ </span>Monthly Active Users</p>
        </div>
        <div class="features2">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle2">
          <p class="core2">MAU Overage Rate</p>
          </div>
        <div class="features3">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle3">
          <p class="core3"><span class="opaque">100 </span>Concurrent Included</p>
        </div>
        <div class="features4">
          <img src="@/assets/circlecheck.png" alt="arrow image" class="circle4">
          <p class="core4">Limited Message Storage</p>
        </div>
        <hr class="double">
        <div class="last">
          <router-link to="/" class="lasttext">Get Started</router-link>
          <img src="@/assets/lastarrow.png" alt="arrow image" class="lastarrow">
        </div>
    </div>
  </div>
  <p id="trust">Trusted by experts at</p>
  <img src="@/assets/screenshot.png" alt="brand logos" class="screenshot">
  <div class="dropcontainer">
    <h3 id="common">Commonly asked questions</h3>
    <p id="ship">Ship in-app chat messaging with all the features your users expect.</p>
    <div class="dropcontent dropcontent1" @click="toggle1">
      <p class="droptext">How is MAU calculated?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available1:available1}">
    </div>
    <div class="droppingsblock" v-if="active1">
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <div class="dropcontent" @click="toggle2">
      <p class="droptext">What is the difference between Starter, Pro, and Enterprise plans?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available2:available2}">
    </div>
    <div class="droppingsblock" v-if="active2" >
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <div class="dropcontent" @click="toggle3">
      <p class="droptext">What happens if I hit my MAU limit?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available3:available3}">
    </div>
    <div class="droppingsblock" v-if="active3">
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <div class="dropcontent" @click="toggle4">
      <p class="droptext">How do I purchase higher levels of support?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available4:available4}">
    </div>
    <div class="droppingsblock" v-if="active4">
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <div class="dropcontent" @click="toggle5">
      <p class="droptext">What other limits do I need to be aware of?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available5:available5}">
    </div>
    <div class="droppingsblock" v-if="active5">
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <div class="dropcontent" @click="toggle6">
      <p class="droptext">Is every feature automatically included in the enterprise plan?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available6:available6}">
    </div>
    <div class="droppingsblock" v-if="active6">
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <div class="dropcontent" @click="toggle">
      <p class="droptext">Do the prices listed on the pricing page include tax?</p>
      <img src="@/assets/Mask.png" alt="dropdown arrow" class="mask" :class="{available:available}">
    </div>
    <div class="droppingsblock" v-if="active">
      <p class="droppings">Tax is not included in the prices listed on the pricing page. Tax will be included in your billing receipts.</p>
    </div>
    <p id="got">Got additional questions?</p>
    <p id="we">We would love to have a chat with you.</p>
    <button id="reach">
      <router-link to="/" id="contact">Contact Support</router-link> 
      <img src="@/assets/bluearrow.png" alt="arrow" id="bluearrow">
    </button>
  </div>
  <div class="chatbox">
    <div class="chatters">
      <p id="chattext">CHAT</p>
      <h2 id="see">See the all-in-one chat system in action</h2>
      <p id="only">The only tool you will need to power conversations and interactions on your product. <span id="go">Go live within days.</span></p>
      <button class="startbtn">
        <router-link to="/" id="start">Start Demo</router-link>
        <img src="@/assets/blackarrow.png" alt="arrow" id="blackarrow">
      </button>
    </div>
    <div class="chatscontainer">
      <img src="@/assets/chats.png" alt="chatbox" id="chats">
    </div>
  </div>
  <div class="bluebox">
    <div class="firstcolumn"> 
      <div class="firstone">
        <h2 id="ready">Ready to have a chat?</h2>
        <p id="love">We'd love to talk about your messaging strategy and help make your software more conversational.</p>
      </div>
      <div class="secondone">
        <div id="talkbtn">
          <p id="talkrbn">Talk To Sales</p>
          <img src="@/assets/whitearrow.png" alt="arrow" id="whitearrow">
        </div>
        <div id="trybtn">
          <p id="tryrbn">Try Robin</p>
          <img src="@/assets/whitearrow.png" alt="arrow" id="whitearrow1">
        </div>
      </div>
    </div>
    <hr class="bluerule">
    <div class="lastflex">
      <div class="rob">
        <img src="@/assets/robin1.png" alt="arrow" id="robin1">
      </div>
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
    <hr class="lastrule">
    <div class="specialflex">
      <router-link to="/" class="specialtext1">© 2021 Robin Inc.</router-link>
      <router-link to="/" class="specialtext">Terms of Service</router-link>
      <router-link to="/" class="specialtext">Privacy Policy</router-link>
      <router-link to="/" class="specialtext">Cookie Settings</router-link>
      <router-link to="/" class="specialtext4">Sub-Processors</router-link>
    </div>
  </div>
</template>

<script>


export default {
  name: 'HomeView',
  components: {
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

<style scoped>
#starter{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
color: #FFFFFF
}

.available{
transform: rotate(180deg);
}

.available1{
transform: rotate(180deg);
}

.available2{
transform: rotate(180deg);
}

.available3{
transform: rotate(180deg);
}

.available4{
transform: rotate(180deg);
}

.available5{
transform: rotate(180deg);
}

.available6{
transform: rotate(180deg);
}

.robincontainer{
margin-left: 49px;
margin-right: 120px;
}

.routes{
width: 730px;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: auto auto auto auto;
padding: auto 0 auto 0;
}

.routes2{
width: 225px;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: auto 49px auto 0;
padding: auto 0 auto 0;
align-items: center;
}

.droppings{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 19px;
line-height: 30px;
color: #000000;
opacity: 0.8;
margin-block-start: 0;
margin-block-end: 0;
background: #FFFFFF;
padding: 27px 35px 37px 50px;
overflow-wrap: normal; 
}

.droppingsblock{
width: 879px;
background: #FFFFFF;
margin: 0 auto 0 auto;
overflow-wrap: normal;
display: flex;
flex-direction: row;
margin-block-start: 0;
margin-block-end: 0;
}

.top{
position: fixed;
width: 100%;
height: 80px;
left: 0px;
top: 0px;
background: #FFFFFF;
box-shadow: 0px 10px 20px rgba(0, 104, 255, 0.09);
display: flex;
flex-direction: row;
flex-wrap: wrap;
align-items: center;
z-index: 1000;
overflow-wrap: normal;
}

.home{
text-decoration: none;
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 14px;
line-height: 16px;
color: #000000;
opacity: 0.6;
}

.home1{
text-decoration: none;
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 14px;
line-height: 16px;
color: #000000;
opacity: 0.2;

}

.home2{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 14px;
line-height: 18px;
text-align: center;
color: #476BD2;
text-decoration: none;
}

#get{
width: 131px;
height: 40px;
background: #476BD2;
border-radius: 30.5px;
border-width: 0;
text-align: center;
}

#gettext{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 14px;
line-height: 18px;
text-align: center;
color: #FFFFFF;
text-decoration: none;
line-height: 40px;
}

#robin{
margin-block-start: 0;
margin-block-end: 0;
}

.firstdiv{
width: 100%;
text-align: center;
}

#simple{
width: 100%;
max-width: 765px;
margin: 228px auto 28px auto;
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 50px;
line-height: 54px;
text-align: center;
color: #000000;
}

#the{
width: 100%;
height: 25px;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 25px;
text-align: center;
color: #000000;
opacity: 0.8;
}

#btn1{
width: 207px;
height: 50px;
background: #4568D1;
border-width: 0;
border-radius: 30.5px;
margin: 32px auto 91px auto;
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
text-align: center;
color: #FFFFFF;
}

#ticker{
padding-left: 44px;
}

.boxes{
margin: 0 auto 0 auto;
width: 100%;
max-width: 1294px;
display: flex;
flex-direction: row;
justify-content: space-around;
}

#box1{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
}

#box1:hover{
border: 1px solid #d79232;
}

#box2:hover{
border: 1px solid #d79232;
}

#box3:hover{
border: 1px solid #d79232;
}

#box4:hover{
border: 1px solid #d79232;
}

#box2{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin-left: 18px;
}

#box3{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin-left: 18px;
}

#box4{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin-left: 18px;
}

.maroon{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 18px;
line-height: 19px;
color: #EA8D51;
margin: 36px auto 0 28px;;
}

.dollars{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 35px;
color: #000000;
line-height: 45px;
margin: 8px auto 0 28px;
}

hr.single{
width: 257px;
height: 0px;
opacity: 0.2;
border: 1px solid #BBC1D6;
margin: 16px auto 0 auto;
background: #BBC1D6;
}

.circle{
width: 16px;
height: 16px;
padding: 0;
}

.circle1{
width: 16px;
height: 16px;
}

.circle2{
width: 16px;
height: 16px;
}

.circle3{
width: 16px;
height: 16px;
}

.circle4{
width: 16px;
height: 16px;
}

.core{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 20px;
color: #485476;
opacity: 0.8;
padding-left: 10.67px;
}

.core1{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 20px;
color: #485476;
opacity: 0.8;
padding-left: 10.67px;
}

.core2{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 20px;
color: #485476;
opacity: 0.8;
padding-left: 10.67px;
}

.core3{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 20px;
color: #485476;
opacity: 0.8;
padding-left: 10.67px;
}

.core4{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 20px;
color: #485476;
opacity: 0.8;
padding-left: 10.67px;
}

.features{
margin-top: 18px;
margin-left: 28px;
display: flex;
flex-direction: row;
justify-content: flex-start;
align-items: center;
width: auto;
height: 20px;
}

.features1{
margin-top: 30px;
margin-left: 28px;
display: flex;
flex-direction: row;
justify-content: flex-start;
align-items: center;
width: auto;
height: 20px;
}

.features2{
margin-top: 30px;
margin-left: 28px;
display: flex;
flex-direction: row;
justify-content: flex-start;
align-items: center;
width: auto;
height: 20px;
}

.features3{
margin-top: 30px;
margin-left: 28px;
display: flex;
flex-direction: row;
justify-content: flex-start;
align-items: center;
width: auto;
height: 20px;
}

.features4{
margin-top: 30px;
margin-left: 28px;
display: flex;
flex-direction: row;
justify-content: flex-start;
align-items: center;
width: auto;
height: 20px;
}

.last{
display: flex;
flex-direction: row;
justify-content: flex-start;
align-items: center;
margin-left: 28px;
margin-top: 27px;
}

.lasttext{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
color: #4568D1;
margin-block-start: 0;
margin-block-end: 0;
text-decoration: none;
}

.lastarrow{
width: 10px;
margin-left: 6px;
}

hr.double{
margin-block-start: 0;
margin-block-end: 0;
margin-top: 52px;
width: 257px;
height: 0px;
opacity: 0.2;
border: 1px solid #BBC1D6;
background: #BBC1D6;
}

.opaque{
opacity: 100%;
font-weight: 700;
}

#trust{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 15px;
line-height: 18px;
text-align: center;
text-transform: uppercase;
color: #000000;
opacity: 0.4;
margin-top: 91px;
}

.screenshot{
width: 1011px;
max-width: 100%;
height: 103px;
margin: 19px auto 0;
text-align: center;
display: block;
}

.dropcontainer{
width: 100%;
max-width: 1238px;
height: auto;
background: #F5F7FC;
border-radius: 25px;
margin: 91px auto 0 auto;
padding-bottom: 116px
}

#common{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 35px;
line-height: 41px;
text-align: center;
color: #000000;
text-align: center;
margin-block-start: 0;
margin-block-end: 0;
padding-top: 71px;
}

#ship{
width: 362px;
height: 60px;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 19px;
line-height: 30px;
text-align: center;
color: #000000;
opacity: 0.8;
text-align: center;
margin-block-start: 0;
margin-block-end: 0;
margin: 23px auto;
}

.droptext{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 20px;
line-height: 22px;
color: #000000;
padding: 27px 0 37px 50px;
margin-block-start: 0;
margin-block-end: 0;
}

.dropcontent{
width: 879px;
height: 86px;
background: #FFFFFF;
margin: 20px auto 0 auto;
display: flex;
flex-direction: row;
justify-content: space-between;
}

.dropcontent1{
margin: 35px auto 0 auto;
}

.mask{
height: 8px;
width: 14px;
border-radius: 0px;
margin: 39px 39px 39px;
}

#got{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 17px;
line-height: 20px;
text-align: center;
color: #000000;
margin-top: 68px;
}

#we{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 30px;
color: #000000;
opacity: 0.8;
margin-top: 8px;
text-align: center;
}

#reach{
box-sizing: border-box;
width: 207px;
height: 50px;
background: #FFFFFF;
border-radius: 30.5px;
display: flex;
flex-direction: row;
align-items: center;
margin: 20px auto 0 auto;
border-width: 0;
}

#contact{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
color: #4568D1;
padding-left: 26px;
padding-right: 23px;
}

#bluearrow{
width: 10px;
}

.chatbox{
width: 100%;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: 0 0 0 0;
margin-block-start: 0;
margin-block-end: 0;
}

.chatters{
width: 50%;
display: flex;
flex-direction: column;
}

.chatscontainer{
width: 50%;
}

#chats{
width: 100%;
margin-top: 46px;
}

#chattext{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 15px;
line-height: 18px;
color: #000000;
opacity: 0.4;
margin-block-start: 0;
margin-block-end: 0;
margin: 119px auto 0 217px;
}

#see{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 35px;
line-height: 41px;
color: #000000;
margin-block-start: 0;
margin-block-end: 0;
margin: 22px auto 0 217px;
max-width: 329px;
}

#only{
margin-block-start: 0;
margin-block-end: 0;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 19px;
line-height: 30px;
color: #000000;
opacity: 0.8;
margin: 37px auto 0 217px;
max-width: 342px;
}

#go{
font-weight: 700;
}

.startbtn{
box-sizing: border-box;
width: 207px;
height: 50px;
border: 1px solid #000000;
border-radius: 30.5px;
margin: 82px auto auto 217px;
display: flex;
flex-direction: row;
align-items: center;
background: #FFFFFF;
}

#start{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
color: #333333;
padding-left: 36px;
text-decoration: none;
}

#blackarrow{
width: 10px;
height: 8px;
margin-left: 52px;
}

.bluebox{
width: 100%;
height: auto;
background: #0C1F55;
margin: auto 0 0 0;
display: flex;
flex-direction: column;
margin-block-start: 0;
margin-block-end: 0;
}

.firstcolumn{
width: 100%;
display: flex;
flex-direction: row;
}

.firstone{
margin: o auto 0 0;
display: flex;
flex-direction: column;
width: 52%;
}

.secondone{
display: flex;
flex-direction: row;
justify-content: space-evenly;
width: 48%;
margin: 0 auto 0 auto 0;
}

#ready{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 43px;
line-height: 51px;
color: #FFFFFF;
margin: 84px auto 0 144px;
Width: 500px;
}

#love{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 35px;
color: #FFFFFF;
opacity: 0.7;
margin-block-start: 0;
margin-block-end: 0;
margin: 23px auto 0 144px;
max-Width: 500px;
}

#talkbtn{
width: 207px;
height: 50px;
background: #4568D1;
border-radius: 30.5px;
display: flex;
flex-direction: row;
align-items: center;
margin-top: 135px;
margin-right: 15px;
justify-content: space-between;
}

#trybtn{
box-sizing: border-box;
width: 207px;
height: 50px;
border: 1px solid;
border-radius: 30.5px;
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
margin-top: 135px;
}

#talkrbn{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
text-align: center;
color: #FFFFFF;
margin-left: 21px;
}

#tryrbn{
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 20px;
text-align: center;
color: #FFFFFF;
margin-left: 21px;
}

#whitearrow{
margin-right: 25px;
}

#whitearrow1{
margin-right: 25px;
}

hr.bluerule{
width: 1100px;
opacity: 0.1;
margin: 98px auto 0 auto;
text-align: center;
border: 1px solid #FFFFFF;
background: #ffffff;
}

hr.lastrule{
width: 1100px;
opacity: 0.1;
border: 1px solid #FFFFFF;
background: #ffffff;
text-align: center;
}

.lastflex{
display: flex;
width: 100%;
height: 308px;
flex-direction: row;
}

.robdets1{
display: flex;
flex-direction: column;
margin: 0 119px 0 auto;
}

.robdets2{
display: flex;
flex-direction: column;
margin: 0 127px 0 auto;
}

.robtext{
text-decoration: none;
width: 115px;
font-family: 'Zona Pro';
font-style: normal;
font-weight: 600;
font-size: 12px;
line-height: 14px;
color: #FFFFFF;
margin-top: 32px;
}

.robtext1{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 17px;
text-transform: uppercase;
color: #FFFFFF;
opacity: 0.4;
margin-top: 50px;
}

.rob{
width: 52%;
margin: 0 auto 0 0;
}

#robin1{
margin: 43px auto 0 144px;
}

.lastrule{
width: 1174px;
opacity: 0.1;
border: 1px solid #FFFFFF;
text-align: cemter;
margin-block-start: 0;
margin-block-end: 0;
margin-top: 50px;
}

.specialtext{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 13px;
line-height: 17px;
color: #FFFFFF;
opacity: 0.5;
margin-right: 40px;
}

.specialtext4{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 13px;
line-height: 17px;
color: #FFFFFF;
opacity: 0.5;
}

.specialtext1{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 18px;
color: #FFFFFF;
opacity: 0.3;
margin: 0 500px 0 144px; 
}

.specialflex{
margin-top: 31px;
margin-bottom: 31px;
overflow-wrap: normal;
}


@media (max-width: 1240px) {

.routes{
width: 730px;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: 10px auto 10px 49px;
padding: auto 0 auto 0;
}

.routes2{
width: 225px;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: auto 49px auto 49px;
padding: auto 0 auto 0;
align-items: center;
}

.boxes{
margin: 0 auto 0 auto;
width: 100%;
display: flex;
flex-direction: column;
} 

#box1{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin: 0 auto 0 auto;
}

#box2{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin: 10px auto 0 auto;
}

#box3{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin: 10px auto 0 auto;
}

#box4{
box-sizing: border-box;
width: 310px;
height: 499px;
background: #F5F7FC;
border: 1px solid #4568D1;
border-radius: 25px;
margin: 10px auto 0 auto;
}

#chattext{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 15px;
line-height: 18px;
color: #000000;
opacity: 0.4;
margin-block-start: 0;
margin-block-end: 0;
margin: 119px auto 0 auto;
width: 329px
}

#see{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 35px;
line-height: 41px;
color: #000000;
margin-block-start: 0;
margin-block-end: 0;
margin: 22px auto 0 auto;
max-width: 329px;
}

#only{
margin-block-start: 0;
margin-block-end: 0;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 19px;
line-height: 30px;
color: #000000;
opacity: 0.8;
margin: 37px auto 0 auto;
max-width: 342px;
}

.startbtn{
width: 207px;
height: 50px;
border: 1px solid #000000;
border-radius: 30.5px;
margin: 82px auto auto auto;
display: flex;
flex-direction: row;
align-items: center;
}

.dropcontent{
width: 100%;
min-height: 86px;
height: auto;
background: #FFFFFF;
margin: 20px auto 0 auto;
display: flex;
flex-direction: row;
justify-content: space-between;
}

.droppingsblock{
width: 100%;
background: #FFFFFF;
margin: 0 auto 0 auto;
overflow-wrap: normal;
display: flex;
flex-direction: row;
margin-block-start: 0;
margin-block-end: 0;
}

#chats{
width: 100%;
height: auto;
margin-top: 46px;
}

.top{
position: fixed;
width: 100%;
min-height: 80px;
height: auto;
left: 0px;
top: 0px;
background: #FFFFFF;
box-shadow: 0px 10px 20px rgba(0, 104, 255, 0.09);
display: flex;
flex-direction: row;
align-items: center;
z-index: 1000;
overflow-wrap: normal;
}

.robdets1{
display: flex;
flex-direction: column;
margin: 0 auto 0 auto;
}

.robdets2{
display: flex;
flex-direction: column;
margin: 0 auto 0 auto;
}

.rob{
margin: 0 auto 0 0;
width: 52%;
}

#robin1{
margin: 43px auto 0 0;
}

.specialtext{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 13px;
line-height: 17px;
color: #FFFFFF;
opacity: 0.5;
margin-right: 2.8%;
word-wrap: break-word
}


.specialtext1{
text-decoration: none;
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 18px;
color: #FFFFFF;
opacity: 0.3;
margin-left: 0; 
margin-right: 10%;
}

.specialflex{
margin-top: 31px;
margin-bottom: 31px;
overflow-wrap: normal;
}

.secondone{
display: flex;
flex-direction: column;
justify-content: space-evenly;
align-items: center;
width: auto;
}

#ready{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 43px;
line-height: 51px;
color: #FFFFFF;
margin: 84px auto 0 0;
Width: 500px;
}

#love{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 35px;
color: #FFFFFF;
opacity: 0.7;
margin: 23px auto 0 0;
max-Width: 500px;
}
}

@media (max-width: 440px){
#talkbtn{
width: 147px;
height: 50px;
background: #4568D1;
border-radius: 30.5px;
display: flex;
flex-direction: row;
align-items: center;
margin-top: 135px;
margin-right: 15px;
justify-content: space-between;
}

#trybtn{
box-sizing: border-box;
width: 147px;
height: 50px;
border: 1px solid;
border-radius: 30.5px;
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
margin-top: 135px;
}

#ready{
font-family: 'Zona Pro';
font-style: normal;
font-weight: 700;
font-size: 43px;
line-height: 51px;
color: #FFFFFF;
margin: 84px auto 0 0;
max-Width: 400px;
}

#love{
font-family: 'Google Sans';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 35px;
color: #FFFFFF;
opacity: 0.7;
margin: 23px auto 0 0;
max-Width: 400px;
}

.robincontainer{
margin-left: 29px;
margin-right: 29px;
}

.routes{
width: 730px;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: 10px auto 10px 29px;
padding: auto 0 auto 0;
}

.routes2{
width: 225px;
display: flex;
flex-direction: row;
justify-content: space-between;
margin: auto 49px auto 29px;
padding: auto 0 auto 0;
align-items: center;
}

.home{
margin-right: 10px;
}

.home1{
margin-right: 10px;
}
}
</style>