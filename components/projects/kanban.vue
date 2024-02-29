<template>
  <div
    class="bg-gradient-to-r from-red-600 to-indigo-600 px-20 py-20 mt-20 mb-0 mx-auto max-w-5xl rounded-lg flex flex-col items-center text-center"
  >
    <h2 class="text-white text-3xl md:text-6xl">Kanban</h2>
    <p class="text-slate-200 mt-4 text-lg md:text-xl">
      Dynamic workflow board
    </p>
    <div class="flex mt-5">
      <LandingLink href="https://kanban.arnold.su" styleName="inverted">Let's Organize</LandingLink>
    </div>
  </div>
  <div class="mt-5 mb-20">
    <h2 class="text-center text-slate-500">Tech Stack</h2>
    <div
      class="flex gap-8 md:gap-20 items-center justify-center mt-5 flex-wrap"
    >
      <Icon class="h-8 md:h-14" name="simple-icons:nuxtdotjs" size="48" />
      <Icon class="h-8 md:h-14" name="simple-icons:tailwindcss" size="48" />
      <Icon class="h-8 md:h-14" name="simple-icons:vuedotjs" size="48" />
      <Icon class="h-8 md:h-14" name="simple-icons:python" size="48" />
      <Icon class="h-8 md:h-12" name="simple-icons:solidity" size="48" />
      <Icon class="h-8 md:h-12" name="simple-icons:django" size="48" />
      <Icon class="h-8 md:h-12" name="simple-icons:cplusplus" size="48" />
    </div>
  </div>
  <hr>
</template>
