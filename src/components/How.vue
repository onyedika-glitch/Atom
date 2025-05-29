<template>
  <section class="w-full py-16 px-2 md:px-8 bg-white flex flex-col items-center">
    <div class="max-w-5xl w-full mx-auto">
      <p class="text-[#1cb5e0] font-medium mb-2 text-center">How We Work</p>
      <h2 class="text-3xl md:text-4xl font-light text-gray-800 text-center mb-10">Collaboration is at the heart of everything we do.</h2>
      <div class="flex flex-col md:flex-row gap-10 items-start justify-center">
        <!-- Accordion -->
        <div class="flex-1 min-w-[260px] max-w-md w-full">
          <!-- Discover (open) -->
          <div class="mb-2">
            <div class="flex items-center justify-between cursor-pointer border-b border-gray-300 pb-2">
              <span class="font-medium text-lg text-gray-800">Discover</span>
              <span class="text-xl text-gray-400">&#9660;</span>
            </div>
            <div class="py-3 pl-1">
              <p class="text-gray-500 text-sm mb-3">We dig deep to understand your needs, users, and goals.</p>
              <button class="border border-[#1cb5e0] text-[#1cb5e0] px-4 py-1 rounded-md font-semibold text-sm hover:bg-[#1cb5e0] hover:text-white transition">Get Started</button>
            </div>
          </div>
          <!-- Design (closed) -->
          <div class="mb-2">
            <div class="flex items-center justify-between cursor-pointer border-b border-gray-300 pb-2">
              <span class="font-medium text-lg text-gray-400">Design</span>
              <span class="text-xl text-gray-300">&#9660;</span>
            </div>
          </div>
          <!-- Develop (closed) -->
          <div class="mb-2">
            <div class="flex items-center justify-between cursor-pointer border-b border-gray-300 pb-2">
              <span class="font-medium text-lg text-gray-400">Develop</span>
              <span class="text-xl text-gray-300">&#9660;</span>
            </div>
          </div>
          <!-- Deliver (closed) -->
          <div>
            <div class="flex items-center justify-between cursor-pointer border-b border-gray-300 pb-2">
              <span class="font-medium text-lg text-gray-400">Deliver</span>
              <span class="text-xl text-gray-300">&#9660;</span>
            </div>
          </div>
        </div>
        <!-- Image -->
        <div class="flex-1 flex items-center justify-center min-w-[300px]">
          <div class="w-full max-w-md h-72 md:h-80 bg-gray-200 rounded-2xl overflow-hidden flex items-center justify-center">
            <!-- Placeholder for image -->
            <span class="text-gray-400 text-3xl">IMG</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts" setup>
// No script logic needed for static how-we-work section
</script>

<style>

</style>