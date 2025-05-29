<template>
  <section class="w-full py-16 px-2 md:px-8 bg-white flex flex-col items-center">
    <div class="relative w-full max-w-6xl mx-auto flex flex-col md:flex-row items-start justify-between min-h-[400px]">
      <!-- Left side -->
      <div class="flex-1 flex flex-col justify-center z-10">
        <div class="relative">
          <span class="absolute -top-16 left-0 text-[7rem] md:text-[10rem] font-extrabold text-[#eaf6fa] select-none pointer-events-none leading-none">Contact</span>
          <h2 class="text-3xl font-light text-gray-800 mb-8 mt-8 md:mt-0 relative">Leave us a message</h2>
        </div>
        <a href="#" class="text-[#1cb5e0] text-sm font-medium hover:underline">Follow Us</a>
      </div>
      <!-- Right side: Contact form -->
      <form class="flex-1 w-full max-w-xl ml-0 md:ml-12 mt-12 md:mt-0 z-10">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
          <div>
            <label class="block text-xs text-gray-500 mb-1">Name</label>
            <input type="text" class="w-full border-b border-gray-300 focus:border-[#1cb5e0] outline-none py-1 bg-transparent" />
          </div>
          <div>
            <label class="block text-xs text-gray-500 mb-1">Company</label>
            <input type="text" class="w-full border-b border-gray-300 focus:border-[#1cb5e0] outline-none py-1 bg-transparent" />
          </div>
          <div>
            <label class="block text-xs text-gray-500 mb-1">Email</label>
            <input type="email" class="w-full border-b border-gray-300 focus:border-[#1cb5e0] outline-none py-1 bg-transparent" />
          </div>
          <div>
            <label class="block text-xs text-gray-500 mb-1">Phone</label>
            <input type="text" class="w-full border-b border-gray-300 focus:border-[#1cb5e0] outline-none py-1 bg-transparent" />
          </div>
        </div>
        <div class="mb-6">
          <label class="block text-xs text-gray-500 mb-1">Write your message to us</label>
          <textarea rows="3" class="w-full border-b border-gray-300 focus:border-[#1cb5e0] outline-none py-1 bg-transparent resize-none"></textarea>
        </div>
        <div class="flex justify-end">
          <button type="submit" class="bg-[#1cb5e0] text-white px-8 py-2 rounded transition hover:bg-[#00bfae]">Send</button>
        </div>
      </form>
    </div>
  </section>
</template>

<script lang="ts" setup>
// No script logic needed for static contact section
</script>

<style>

</style>