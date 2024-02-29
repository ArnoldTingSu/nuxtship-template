<script setup>
definePageMeta({
  layout: "landing",
});

const TeamImg1 = "https://avatars.githubusercontent.com/u/26914510";

const me = [
  {
    name: "Arnold Su",
    title: "Developer",
    avatar: {
      src: TeamImg1,
      width: 480,
      height: 560,
    },
  },
];
</script>

<template>
  <title>Arnold Su - About</title>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>About</template>
      <template v-slot:desc>I am just a passionate dev.</template>
    </LandingSectionhead>

    <div class="flex flex-col gap-3 mx-auto max-w-4xl mt-16">
      <h2 class="font-bold text-3xl text-gray-800">
        Empowering the world by continuous effort toward excellence.
      </h2>
      <p class="text-lg leading-relaxed text-slate-500">
        As a culturally versatile developer with a passion for global exploration, I thrive on traversing diverse industry landscapes. My varied background enriches my perspective, offering a unique blend of experiences and skills to contribute to your team. I am enthusiastic about channeling my focus and expertise to enhance the collaborative dynamics within your organization.
      </p>
    </div>
    <div class="flex justify-center mt-10">
      <div v-for="item of me" class="group">
        <div class="w-full aspect-square">
          <img
            :src="item.avatar.src"
            :width="item.avatar.width"
            :height="item.avatar.height"
            format="avif"
            alt="Team"
            class="w-full h-full object-cover rounded transition group-hover:-translate-y-1 group-hover:shadow-xl"
          />
        </div>

        <div class="mt-4 text-center">
          <h2 class="text-lg text-gray-800">{{ item.name }}</h2>
          <h3 class="text-sm text-slate-500">{{ item.title }}</h3>
        </div>
      </div>
      <!-- {
        team.map((item) => (
          <div class="group">
            <div class="w-full aspect-square">
              <Image
                {...item.avatar}
                format="avif"
                alt="Team"
                class="w-full h-full object-cover rounded transition  group-hover:-translate-y-1 group-hover:shadow-xl"
              />
            </div>

            <div class="mt-4 text-center">
              <h2 class="text-lg text-gray-800"> {item.name}</h2>
              <h3 class="text-sm text-slate-500"> {item.title}</h3>
            </div>
          </div>
        ))
      } -->
    </div>
  </LandingContainer>
</template>
