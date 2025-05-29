<template>
  <section class="relative w-full bg-white py-16 flex flex-col items-center overflow-hidden">
    <!-- Subtle grid background placeholder -->
    <div class="absolute inset-0 pointer-events-none select-none opacity-30 z-0">
      <!-- Add SVG or pattern here if desired -->
    </div>
    <div class="relative z-10 max-w-6xl mx-auto w-full grid grid-cols-1 md:grid-cols-3 gap-8 items-center">
      <!-- Left column -->
      <div class="flex flex-col gap-8">
        <div class="bg-white rounded-xl shadow p-5 flex flex-col gap-2">
          <div class="flex items-center justify-between">
            <span class="font-semibold text-gray-800 text-base">Partner with Us to Shape the Future of AI</span>
            <span class="text-2xl text-[#1cb5e0]">&#8594;</span>
          </div>
          <p class="text-gray-500 text-sm">Atom builds smart, scalable AI solutions to power Africa's growth. We're driven by excellence, innovation, and a bold vision to lead the continent's tech future.</p>
        </div>
        <div class="bg-white rounded-xl shadow p-5 flex flex-col gap-2">
          <div class="flex items-center justify-between">
            <span class="font-semibold text-gray-800 text-base">Smarter Operations with AI</span>
            <span class="text-2xl text-[#1cb5e0]">&#8594;</span>
          </div>
          <p class="text-gray-500 text-sm">We've helped businesses: Boost operational efficiency by up to 60%, Achieve 4x user engagement, Accelerate go-to-market timelines by 40%.</p>
        </div>
      </div>
      <!-- Center column -->
      <div class="flex flex-col items-center justify-center">
        <div class="bg-white rounded-xl h-40 w-full mb-4 flex items-center justify-center overflow-hidden">
          <img src="@/assets/Ai.png" alt="Handyman Product" class="object-cover w-full h-full" />
        </div>
        <div class="text-center">
          <h2 class="text-2xl md:text-3xl font-light text-gray-800 mb-2">Atom Group</h2>
          <p class="text-gray-500 text-base">At Atom, we are not just building products, we're reshaping industries.</p>
        </div>
      </div>
      <!-- Right column -->
      <div class="flex flex-col gap-8">
        <div class="bg-white rounded-xl shadow p-5 flex flex-col gap-2">
          <div class="flex items-center justify-between">
            <span class="font-semibold text-gray-800 text-base">Redefining Ai for Africa's Growth</span>
            <span class="text-2xl text-[#1cb5e0]">&#8592;</span>
          </div>
          <p class="text-gray-500 text-sm">As an emerging force in Africa's growing tech ecosystem, Atom is redefining what's possible with AI. From automating core business operations to driving customer growth and predictive intelligence, our solutions are built to scale impact.</p>
        </div>
        <div class="bg-white rounded-xl shadow p-5 flex flex-col gap-2">
          <div class="flex items-center justify-between">
            <span class="font-semibold text-gray-800 text-base">Intelligent Products Transformative Impact</span>
            <span class="text-2xl text-[#1cb5e0]">&#8592;</span>
          </div>
          <p class="text-gray-500 text-sm">With every product deployed, Atom moves closer to its vision: building intelligent systems that power Africa's next wave of transformation.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts" setup>
// No script logic needed for static group section
</script>

<style>

</style>