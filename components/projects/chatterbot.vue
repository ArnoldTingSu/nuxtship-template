<template>
  <div
    class="bg-gradient-to-r from-sky-600 to-emerald-600 px-20 py-20 mt-20 mx-auto max-w-5xl rounded-lg flex flex-col items-center text-center"
  >
    <h2 class="text-white text-3xl md:text-6xl">ChatterBOX</h2>
    <p class="text-slate-200 mt-4 text-lg md:text-xl">
      GPT-Agent Chatbot
    </p>
    <div class="flex mt-5">
      <LandingLink href="https://chatterboxai.vercel.app" styleName="inverted" target="_blank">Start Chatting</LandingLink>
    </div>
  </div>
  <div class="mt-5 mb-20">
    <h2 class="text-center text-slate-500">Tech Stack</h2>
    <div
      class="flex gap-8 md:gap-20 items-center justify-center mt-5 flex-wrap"
    >
      <Icon class="h-8 md:h-14" name="simple-icons:nuxtdotjs" size="48" />
      <Icon class="h-8 md:h-14" name="simple-icons:vuedotjs" size="48" />
      <Icon class="h-8 md:h-14" name="simple-icons:typescript" size="48" />
      <Icon class="h-8 md:h-12" name="simple-icons:openai" size="48" />
      <Icon class="h-8 md:h-14" name="simple-icons:tailwindcss" size="48" />
      <Icon class="h-8 md:h-12" name="simple-icons:vercel" size="48" />
    </div>
  </div>
  <hr>
</template>
