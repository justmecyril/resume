<template>
  <div class="mx-36">
    <h1 class="mt-4 text-white text-9xl font-neue-bold">CYRIL SEMABIA.</h1>
    <div class="flex gap-[14rem] mt-12 text-sm text-white ml-[24rem] font-neue">
      <p class="cursor-pointer hover:text-right">
        https://www.linkedin.com/in/cyril-semabia
      </p>
      <p class="cursor-pointer">https://github.com/justmecyril</p>
    </div>
    <div class="flex gap-8 mt-12 text-white">
      <p class="text-4xl font-neue-bold">
        A Front-End Web Developer operating from my base in Accra, Ghana.
      </p>
      <p class="text-base font-neue-regular">
        I love to translate designs into clean, elegant, functional and
        responsive User Interfaces. <br />I have industry experience building
        websites and web applications using HTML, CSS, SCSS, JavaScript,
        Vue/Vuex, React/Redux, NextJs and quite recently TypeScript.
      </p>
    </div>
    <div class="flex gap-8 mt-24">
      <img
        src="@/assets/images/pic.png"
        alt="Profile Picture"
        class="w-[35rem] ml-40"
      />
      <div class="mt-12 text-white">
        <p class="mb-2 text-base font-neue">Available for new projects.</p>
        <a
          href="mailto:kofisem@gmail.com"
          target="_blank"
          class="text-lg font-semibold cursor-pointer font-neue-bold"
          >Get in touch</a
        >
      </div>
    </div>
    <particles-view />
  </div>
</template>
<script>
import ParticlesView from "@/components/ParticlesView.vue";
export default {
  components: { ParticlesView },
};
</script>
