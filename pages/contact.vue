<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <title>Arnold Su - Contact</title>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>Contact</template>
      <template v-slot:desc>Happy to lend a hand.</template>
    </LandingSectionhead>

    <div class="grid md:grid-cols-2 gap-10 mx-auto max-w-4xl mt-16">
      <div>
        <h2 class="font-medium text-2xl text-gray-800">
          Contact Arnold
        </h2>
        <p class="text-lg leading-relaxed text-slate-500 mt-3">
          Have a project idea? A vision? I am here to help. 
          <br>
          Drop some info or send an email.
        </p>
        <div class="mt-5">
          <div class="flex items-center mt-2 space-x-2 text-gray-600">
            <Icon class="text-gray-400 w-4 h-4" name="uil:map-marker" />
            <span>Los Angeles, California</span>
          </div>
          <div class="flex items-center mt-2 space-x-2 text-gray-600">
            <Icon class="text-gray-400 w-4 h-4" name="uil:envelope" /><a
              href="mailto:me@arnold.su"
              >me@arnold.su</a
            >
          </div>
          <!-- <div class="flex items-center mt-2 space-x-2 text-gray-600">
            <Icon class="text-gray-400 w-4 h-4" name="uil:phone" /><a
              href="tel:+1 (234) 5678 999"
              >+1 (234) 5678 999</a
            >
          </div> -->
        </div>
      </div>
      <div>
        <LandingContactform />
      </div>
    </div>
  </LandingContainer>
</template>
