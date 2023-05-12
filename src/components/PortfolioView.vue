<template>
  <section class="mt-24 portfolio mx-36">
    <h1 class="text-white capitalize font-neue-bold text-7xl heading">
      recent <br />
      projects.
    </h1>
    <div class="mt-12 stacked_cards">
      <main>
        <ul id="cards">
          <li class="card" id="card_1">
            <div class="card__content">
              <div class="text-white">
                <h2 class="text-2xl font-neue-bold">Guard Tracker</h2>
                <p class="font-neue">
                  A system for managing security personnel.
                </p>
                <p class="font-neue-regular">Guard Tracker ● 2022</p>
                <p class="font-neue-regular">VueJs, Tailwind CSS, Supabase</p>
                <p>
                  <a
                    href="https://guardtracker.netlify.app"
                    class="font-neue-regular"
                    >https://guardtracker.netlify.app</a
                  >
                </p>
              </div>
              <figure class="">
                <img
                  src="@/assets/images/GuardTracker.png"
                  alt="Image description"
                  class="border border-white rounded-lg bg-[#286d5d]"
                />
              </figure>
            </div>
          </li>
          <li class="card" id="card_2">
            <div class="card__content">
              <div class="text-white">
                <h2 class="text-2xl font-neue-bold">Last Mile</h2>
                <p class="font-neue">A system for managing ISP clientele.</p>
                <p class="font-neue-regular">Last Mile ● 2021</p>
                <p class="font-neue-regular">
                  VueJs/Vuex, Tailwind CSS, Supabase
                </p>
                <p>
                  <a
                    href="https://last-mile.netlify.app"
                    class="font-neue-regular"
                    >https://last-mile.netlify.app</a
                  >
                </p>
              </div>
              <figure>
                <img
                  src="@/assets/images/LastMile.png"
                  alt="Image description"
                  class="border border-white rounded-lg bg-[#4B0082]"
                />
              </figure>
            </div>
          </li>
          <li class="card" id="card_3">
            <div class="card__content">
              <div class="text-white">
                <h2 class="text-2xl font-neue-bold">Kids Learn</h2>
                <p class="font-neue">
                  An online educative kids video platform.
                </p>
                <p class="font-neue-regular">Kids Learn ● 2022</p>
                <p class="font-neue-regular">VueJs, Tailwind CSS</p>
                <p>
                  <a
                    href="https://kids-learn.netlify.app/"
                    class="font-neue-regular"
                    >https://kids-learn.netlify.app/</a
                  >
                </p>
              </div>
              <figure>
                <img
                  src="@/assets/images/kids-learn.png"
                  alt="Image description"
                  class="bg-yellow-400 border border-white rounded-lg"
                />
              </figure>
            </div>
          </li>
          <li class="card" id="card_4">
            <div class="card__content">
              <div class="text-white">
                <h2 class="font-neue-bold">Roll-Call</h2>
                <p class="font-neue">
                  A simple app for displaying a security company's clientele.
                </p>
                <p class="font-neue-regular">Roll-Call ● 2022</p>
                <p class="font-neue-regular">VueJs, CSS, Typescript</p>
                <p>
                  <a
                    href="https://security-roll-call.netlify.app/"
                    class="font-neue-regular"
                    >https://security-roll-call.netlify.app/</a
                  >
                </p>
              </div>
              <figure>
                <img
                  src="@/assets/images/roll-call.png"
                  alt="Image description"
                  class="bg-gray-400 border rounded-lg"
                />
              </figure>
            </div>
          </li>
        </ul>
      </main>
    </div>
  </section>
</template>
<script>
export default {
  setup() {
    const cards = [
      {
        id: "card_1",
        project: "Guard Tracker",
        description: "A system for managing security personnel.",
        year: "Guard Tracker ● 2022",
        stack: "VueJs/VueXJs, Tailwind CSS, Supabase",
        image: require("@/assets/images/GuardTracker.png"),
      },
      {
        id: "card_1",
        project: "Guard Tracker",
        description: "A system for managing security personnel.",
        year: "Guard Tracker ● 2022",
        stack: "VueJs/VueXJs, Tailwind CSS, Supabase",
        image: require("@/assets/images/GuardTracker.png"),
      },
      {
        id: "card_1",
        project: "Guard Tracker",
        description: "A system for managing security personnel.",
        year: "Guard Tracker ● 2022",
        stack: "VueJs/VueXJs, Tailwind CSS, Supabase",
        image: require("@/assets/images/GuardTracker.png"),
      },
      {
        id: "card_1",
        project: "Guard Tracker",
        description: "A system for managing security personnel.",
        year: "Guard Tracker ● 2022",
        stack: "VueJs/VueXJs, Tailwind CSS, Supabase",
        image: require("@/assets/images/GuardTracker.png"),
      },
    ];

    return { cards };
  },
};
</script>
