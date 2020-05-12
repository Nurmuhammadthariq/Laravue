<template>
  <div class="home">
    <Header/>
    <HeroShayna/>
    <WomanShayna/>
    <InstaShayna/>
    <PartnerShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Home',
  components: {
    Header,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
