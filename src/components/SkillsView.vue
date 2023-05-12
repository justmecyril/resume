<template>
  <div class="mt-32 mx-36">
    <h1 class="text-white text-7xl font-neue-bold">Skills</h1>

    <div class="mt-4 carousal">
      <div class="slider">
        <div class="slide-track">
          <div v-for="(skill, i) in skills" :key="i" class="flex">
            <div class="slide">
              <img :src="skill.logo" alt="Logo" class="w-24 h-14" />
              <h3 class="mt-4 text-lg font-neue-bold">{{ skill.name }}</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  setup() {
    const skills = [
      { id: 1, logo: require("@/assets/images/html.svg"), name: "HTML" },
      { id: 2, logo: require("@/assets/images/css.svg"), name: "CSS" },
      { id: 3, logo: require("@/assets/images/scss.png"), name: "SCSS" },
      {
        id: 4,
        logo: require("@/assets/images/javascript.png"),
        name: "JavaScript",
      },
      { id: 5, logo: require("@/assets/images/react.png"), name: "ReactJs" },
      { id: 6, logo: require("@/assets/images/next.png"), name: "NextJs" },
      { id: 7, logo: require("@/assets/images/vuejs.png"), name: "VueJs" },
      {
        id: 8,
        logo: require("@/assets/images/tailwind.png"),
        name: "Tailwind",
      },
      {
        id: 9,
        logo: require("@/assets/images/supabase.png"),
        name: "Supabase",
      },
      {
        id: 10,
        logo: require("@/assets/images/typescript.png"),
        name: "TypeScript",
      },
      { id: 11, logo: require("@/assets/images/git.png"), name: "Git" },
      { id: 12, logo: require("@/assets/images/html.svg"), name: "HTML" },
      { id: 13, logo: require("@/assets/images/css.svg"), name: "CSS" },
      { id: 14, logo: require("@/assets/images/scss.png"), name: "SCSS" },
      {
        id: 15,
        logo: require("@/assets/images/javascript.png"),
        name: "JavaScript",
      },
      { id: 16, logo: require("@/assets/images/react.png"), name: "ReactJs" },
      { id: 17, logo: require("@/assets/images/next.png"), name: "NextJs" },
      { id: 18, logo: require("@/assets/images/vuejs.png"), name: "VueJs" },
      {
        id: 19,
        logo: require("@/assets/images/tailwind.png"),
        name: "Tailwind",
      },
      {
        id: 20,
        logo: require("@/assets/images/supabase.png"),
        name: "Supabase",
      },
      {
        id: 21,
        logo: require("@/assets/images/typescript.png"),
        name: "TypeScript",
      },
      { id: 22, logo: require("@/assets/images/git.png"), name: "Git" },
    ];

    return { skills };
  },
};
//
</script>

<style lang="scss">
section {
  margin: 0 86px;
}
.carousal body {
  align-items: center;
  background: #e3e3e3;
  display: flex;
  height: 100vh;
  justify-content: center;
}

$animationSpeed: 20s;

// Animation
@keyframes scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(calc(-250px * 7));
  }
}

// Styling
.slider {
  background: black;
  box-shadow: 0 10px 20px -5px rgba(0, 0, 0, 0.125);
  height: 150px;
  margin: auto;
  overflow: hidden;
  position: relative;
  width: 1210px;

  &::before,
  &::after {
    content: "";
    height: 100px;
    position: absolute;
    width: 200px;
    z-index: 2;
  }

  &::after {
    right: 0;
    top: 0;
    transform: rotateZ(180deg);
  }

  &::before {
    left: 0;
    top: 0;
  }

  .slide-track {
    animation: scroll $animationSpeed linear infinite;
    display: flex;
    width: calc(250px * 14);
  }

  .slide {
    height: 200px;
    width: 250px;
    padding-top: 2vh;
  }

  .slide h3 {
    color: white;
  }
}
</style>
