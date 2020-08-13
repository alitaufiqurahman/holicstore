<template>
  <div class="home">
    <Header />
    <BanerHero />
    <BanerProduct />
    <InstaWorka />
    <PartnerLogo />
    <FooterEnd />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import BanerHero from "@/components/BanerHero.vue";
import BanerProduct from "@/components/BanerProduct.vue";
import InstaWorka from "@/components/InstaWorka.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import FooterEnd from "@/components/FooterEnd.vue";

export default {
  name: "Home",
  components: {
    Header,
    BanerHero,
    BanerProduct,
    InstaWorka,
    PartnerLogo,
    FooterEnd
  }
};
</script>
