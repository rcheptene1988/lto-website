<template>
<div>

<Header />
<HeroScene />
<WhatIsStaking />
<ManageYourStakes />
<StakeWithUs />
<Incentives />
<CommunityTools />
<WhyUs />
<OurPhilosophy />
<Footer />


</div>
  <router-view/>
</template>

<script>
import Header from "./components/Header/Header.vue"
import HeroScene from "./components/Homepage/HeroScene.vue"
import WhatIsStaking from "./components/Homepage/WhatIsStaking.vue"
import ManageYourStakes from "./components/Homepage/ManageYourStakes.vue"
import StakeWithUs from "./components/Homepage/StakeWithUs.vue"
import Incentives from "./components/Homepage/Incentives.vue"
import CommunityTools from "./components/Homepage/CommunityTools.vue"
import WhyUs from "./components/Homepage/WhyUs.vue"
import OurPhilosophy from "./components/Homepage/OurPhilosophy.vue"
import Footer from './components/Footer/Footer.vue'


export default {
  components: {
    Header,
    HeroScene,
    WhatIsStaking,
    ManageYourStakes,
    StakeWithUs,
    Incentives,
    CommunityTools,
    WhyUs,
    OurPhilosophy,
    Footer
  },
  // name: "Home",

  computed: {},
  methods: {},
};
</script>


<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}



</style>
