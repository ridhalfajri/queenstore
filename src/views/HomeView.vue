<template>
  <div class="home">
    <HeaderQueen />
    <HeroQueen />
    <WomenBannerQueen />
    <InstaQueen />
    <PartnerQueen />
    <FooterQueen />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderQueen from '@/components/HeaderQueen.vue'
import HeroQueen from '@/components/HeroQueen.vue'
import WomenBannerQueen from '@/components/WomenBannerQueen.vue'
import InstaQueen from '@/components/InstaQueen.vue'
import PartnerQueen from '@/components/PartnerQueen.vue'
import FooterQueen from '@/components/FooterQueen.vue'


export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderQueen,
    HeroQueen,
    WomenBannerQueen,
    InstaQueen,
    PartnerQueen,
    FooterQueen
  }
}
</script>
