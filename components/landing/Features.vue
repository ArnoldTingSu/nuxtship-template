<script setup>
const features = [
  {
    title: "Proficient in Multiple Languages",
    description:
      "Using mutliple languages, enables me to be versatile and make meaningful contributions to diverse projects.",
    icon: "bx:code-alt",
  },
  {
    title: "Strong Problem-Solving Skills",
    description:
      "The ability to analyze and resolve complex issues efficiently and creatively; no task or feature is out of reach.",
    icon: "bx:bxs-cube-alt",
  },
  {
    title: "Version Control Experience(Git)",
    description:
      "Targeting an issue? Proficient in Git for tracking changes, collaborating with teams, and managing code versions.",
    icon: "bx:bxs-data",
  },
  {
    title: "Front and Back-End Proficiency",
    description:
      "Utilizing frameworks to create dynamic and interactive interfaces while streamlining server-side processes.",
    icon: "bx:bxs-adjust",
  },
  {
    title: "Continuous Learning and Adaptability",
    description:
      "Committed to staying updated on industry trends and swiftly adapting to evolving technologies.",
    icon: "bx:bxs-file-find",
  },
  {
    title: "Collaborative Team Player",
    description:
      "Able to work effectively within a team, contribute ideas, and engage in open communication for collective success.",
    icon: "bx:bxs-user",
  },
];
</script>

<template>
  <div class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      Everything you need from a developer
    </h2>
    <p class="text-lg mt-4 text-slate-600">
      I come with batteries included. Taking the best parts of innovative
      tools while researching or developing my own innovations.
    </p>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
