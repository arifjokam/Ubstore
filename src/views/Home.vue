<template>
  <div class="home">
    <HeaderShayna />
    <HeroUb1 />
    <HeroUb2 />
    <InstaUb />
    <LogoPatners />
    <FooterUb />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroUb1 from "@/components/HeroUb1.vue";
import HeroUb2 from "@/components/HeroUb2.vue";
import InstaUb from "@/components/InstaUb.vue";
import LogoPatners from "@/components/LogoPatners.vue";
import FooterUb from "@/components/FooterUb.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroUb1,
    HeroUb2,
    InstaUb,
    LogoPatners,
    FooterUb,
  },
};
</script>
