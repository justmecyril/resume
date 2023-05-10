<template>
  <div>
<hero-view/>
<skills-view/>
<portfolio/>
<contact-view/>
  </div>
</template>




<script>
import HeroView from '@/components/HeroView.vue'
import SkillsView from '@/components/SkillsView.vue'
import Portfolio from '@/components/Portfolio.vue'
import ContactView from '@/components/ContactView.vue'
export default {
 components:{HeroView, SkillsView,Portfolio,ContactView},
setup(){
  return{
 
  }
}
};
</script>
