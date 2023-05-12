<template>
  <div>
    <hero-view />
    <skills-view />
    <portfolio-view />
    <contact-view />
    <footer-view />
  </div>
</template>

<script>
import HeroView from "@/components/HeroView.vue";
import SkillsView from "@/components/SkillsView.vue";
import PortfolioView from "@/components/PortfolioView.vue";
import ContactView from "@/components/ContactView.vue";
import FooterView from "@/components/FooterView.vue";
export default {
  components: { HeroView, SkillsView, PortfolioView, ContactView, FooterView },
  setup() {
    return {};
  },
};
</script>
