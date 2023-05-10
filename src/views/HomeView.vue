<template>
  <div>
<hero-view/>
<about-view/>
<portfolio/>
<contact-view/>
  </div>
</template>




<script>
import HeroView from '@/components/HeroView.vue'
import AboutView from '@/components/AboutView.vue'
import Portfolio from '@/components/Portfolio.vue'
import ContactView from '@/components/ContactView.vue'
export default {
 components:{HeroView, AboutView,Portfolio,ContactView},
setup(){
  return{
 
  }
}
};
</script>
