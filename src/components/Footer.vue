<template>
  <footer class="relative w-full bg-white pt-6 pb-2 px-2 md:px-8 border-t border-gray-100 overflow-hidden">
    <!-- Top nav -->
    <div class="flex flex-col md:flex-row md:items-center md:justify-between max-w-6xl mx-auto w-full mb-2">
      <div class="flex items-center gap-2 mb-2 md:mb-0">
        <span class="w-8 h-8 bg-gray-200 rounded-full flex items-center justify-center text-xl font-bold text-[#1cb5e0]">&#9673;</span>
        <span class="font-bold text-lg text-gray-800">ATOM</span>
      </div>
      <nav class="flex flex-wrap gap-6 text-sm text-gray-700">
        <a href="#" class="hover:underline">Overview</a>
        <a href="#" class="hover:underline">Products</a>
        <a href="#" class="hover:underline">Services</a>
        <a href="#" class="hover:underline">Contact Us</a>
        <a href="#" class="hover:underline">Help</a>
        <a href="#" class="hover:underline">Privacy</a>
      </nav>
    </div>
    <hr class="border-gray-200 my-2" />
    <!-- Copyright and legal -->
    <div class="flex flex-col md:flex-row md:items-center md:justify-between max-w-6xl mx-auto w-full text-xs text-gray-500 mb-8">
      <div class="mb-2 md:mb-0">© 2025 Atom. All rights reserved.</div>
      <div class="flex gap-4 md:gap-6 justify-end">
        <a href="#" class="hover:underline">Terms</a>
        <a href="#" class="hover:underline">Privacy</a>
        <a href="#" class="hover:underline">Cookies</a>
      </div>
    </div>
    <!-- Large faded background text -->
    <div class="absolute left-0 bottom-0 w-full overflow-hidden select-none pointer-events-none">
      <span class="text-[3rem] md:text-[7rem] font-extrabold text-[#eaf6fa] tracking-tight whitespace-nowrap leading-none">ATOM GROUP</span>
    </div>
  </footer>
</template>

<script lang="ts" setup>
// No script logic needed for static footer
</script>

<style>

</style>