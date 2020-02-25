<template>
  <div class="home">
    <!-- Page Preloder -->
    
    <!-- Header Section Begin -->
      <HeaderShayna />
    <!-- Header End -->
      <HeroShayna />
      <BannerShayna />
      <InstagramShayna />
      <PartnerLogo />
      <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import BannerShayna from '@/components/BannerShayna.vue'
import InstagramShayna from '@/components/InstagramShayna.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import FooterShayna from '@/components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    BannerShayna,
    InstagramShayna,
    PartnerLogo,
    FooterShayna,
  }
}
</script>
