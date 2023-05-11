<template>
  <div>
<hero-view/>
<skills-view/>
<portfolio/>
<contact-view/>
<footer-view/>
  </div>
</template>




<script>
import HeroView from '@/components/HeroView.vue'
import SkillsView from '@/components/SkillsView.vue'
import Portfolio from '@/components/Portfolio.vue'
import ContactView from '@/components/ContactView.vue'
import FooterView from '@/components/FooterView.vue'
export default {
 components:{HeroView, SkillsView,Portfolio,ContactView,FooterView},
setup(){
  return{
 
  }
}
};
</script>
