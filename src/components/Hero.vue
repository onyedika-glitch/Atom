<template>
  <section class="relative bg-[#F2FDFF] pb-20 pt-16 px-4 md:px-20 flex flex-col items-center justify-center text-center">
    <!-- Top-right animation -->
    <img
        src="/src/assets/Cube.png"
        alt="Animated graphic"
        class="animated-cube absolute top-10 right-10 w-40 h-40 opacity-30 pointer-events-none"
    />
    <div class="h-10"></div>
    <div class="text-center max-w-3xl mx-auto">
      <!-- Heading -->
      <div class="h-10"></div>
      <h1 class="text-3xl md:text-5xl font-bold leading-tight text-gray-900">
        From
        <span class="text-[#01B8C6] font-extrabold text-4xl">
          Bold Ideas
        </span> to
        <span class="text-[#01B8C6] font-extrabold block mt-2 text-4xl">
          Industry Changing
        </span>
        <span class="block mt-2">Solutions.</span>
      </h1>

      <!-- Breadcrumb-like space -->
      <div class="h-10"></div>

      <!-- Subheading -->
      <p class="text-base md:text-lg text-gray-600">
        Africa’s Emerging AI Powerhouse – Building Tomorrow’s Tech Today.<br />
        Directly states your market positioning and innovative edge.
      </p>
      <div class="h-10"></div>
      <div class="mt-8 flex justify-center gap-4">
        <div class="h-10"></div>
        <router-link
            to="/products"
            class="px-6 py-2 border border-gray-400 rounded-md hover:bg-gray-100 transition cursor-pointer"
        >
          See Our Work
        </router-link>
        <router-link
            to="/contact"
            class="px-6 py-2 bg-[#01B8C6] text-white rounded-md hover:bg-[#00a9b6] transition cursor-pointer"
        >
          Let’s Talk
        </router-link>
      </div>
      <div class="h-10"></div>
    </div>
    <div class="h-10"></div>

    <!-- Hero Image -->
    <div class="mt-12 mx-auto max-w-3xl px-4">
      <img
          src="@/assets/ai-team.jpg"
          alt="AI team"
          class="rounded-2xl w-full object-cover shadow-lg"
      />
    </div>
  </section>
</template>

<script setup>
import { onMounted } from 'vue'
import { gsap } from 'gsap'

onMounted(() => {
  gsap.to('.animated-cube', {
    rotate: 360,
    repeat: -1,
    duration: 10,
    ease: 'linear'
  })
})
</script>
