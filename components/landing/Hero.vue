<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-24 md:order-1 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="https://avatars.githubusercontent.com/u/26914510"
        alt="arnold"
        loading="eager"
        format="avif"
        width="350"
        height="256"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
        Hello!
      </h1>
      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        and welcome to my comprehensive portfolio, a curated compilation of projects, each meticulously documented with the respective tech stack employed.
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href="/projects"
          >Projects</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href="https://github.com/arnoldtingsu"
          target="_blank"
          >GitHub</LandingLink
        >
      </div>
    </div>
  </main>
</template>
