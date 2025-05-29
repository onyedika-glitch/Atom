<template>
  <section class="relative w-full min-h-screen bg-white py-24 px-6 md:px-20 overflow-hidden flex flex-col items-center justify-center text-center">
    <!-- Visible Animated Atom -->
    <div class="absolute left-10 top-10 z-0 opacity-100">
      <img src="@/assets/animated-atom.png" alt="Rotating Atom" class="w-40 h-40 md:w-52 md:h-52 animate-spin-slow" />
    </div>

    <!-- Heading -->
    <div class="relative z-10 max-w-4xl mx-auto text-center mb-16">
      <h2 class="text-4xl md:text-5xl font-light text-gray-800 leading-tight">
        The World of <br />Artificial Intelligence
      </h2>
    </div>
    <div class="h-10"></div>
    <!-- Irregular Staggered Layout -->
    <div class="relative z-10 max-w-6xl mx-auto grid grid-cols-12 gap-6">
      <!-- Tall container on the left -->
      <div class="col-span-12 md:col-span-5 row-span-2 bg-gray-50 rounded-xl shadow p-6 flex items-start gap-4">
        <span class="text-[#1cb5e0] text-3xl">🤖</span>
        <p class="text-gray-700 text-lg">Machine learning allows AI systems to improve over time — just like we learn from experience.</p>
      </div>
      <div class="h-10"></div>
      <!-- Wide card to the right -->
      <div class="col-span-12 md:col-span-7 bg-gray-50 rounded-xl shadow p-6 flex items-start gap-4">
        <span class="text-[#1cb5e0] text-3xl">📊</span>
        <p class="text-gray-700 text-lg">AI analyzes huge amounts of data in seconds, helping businesses make faster, smarter decisions.</p>
      </div>
      <div class="h-10"></div>
      <!-- Shorter wide card below -->
      <div class="col-span-12 md:col-span-7 bg-gray-50 rounded-xl shadow p-6 flex items-start gap-4">
        <span class="text-[#1cb5e0] text-3xl">📱</span>
        <p class="text-gray-700 text-lg">From your smartphone keyboard to Netflix recommendations — AI is behind many tools you use daily.</p>
      </div>
      <div class="h-10"></div>
      <!-- Small box on right -->
      <div class="col-span-12 md:col-span-5 bg-gray-50 rounded-xl shadow p-6 flex items-start gap-4">
        <span class="text-[#1cb5e0] text-3xl">🧩</span>
        <p class="text-gray-700 text-lg">AI isn't one-size-fits-all — businesses can build tailored models that solve their specific challenges.</p>
      </div>
      <div class="h-10"></div>
      <!-- Final full-width container -->
      <div class="col-span-12 bg-gray-50 rounded-xl shadow p-6 flex items-start gap-4">
        <span class="text-[#1cb5e0] text-3xl">🌍</span>
        <p class="text-gray-700 text-lg">AI is revolutionizing healthcare, finance, education, agriculture, and beyond.</p>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// No logic needed
</script>

<style scoped>
@keyframes spin-slow {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.animate-spin-slow {
  animation: spin-slow 25s linear infinite;
}
</style>
