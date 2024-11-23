<template>
    <nav class="fixed top-0 left-0 w-screen bg-white shadow-md z-50 h-fit py-6">
      <!-- Desktop Navbar -->
      <div class="hidden md:flex items-center justify-center">
        <div class="flex items-center space-x-6">
          <span class="font-bold text-xl">Newbyte</span>
          <span class="text-gray-400">|</span>
          <a href="#" class="text-gray-700 hover:text-blue-500">Home</a>
          <a href="#services" class="text-gray-700 hover:text-blue-500">Services</a>
          <a href="#team" class="text-gray-700 hover:text-blue-500">Team</a>
          <a href="#contact" class="text-gray-700 hover:text-blue-500">Contact us</a>
        </div>
      </div>
  
      <!-- Mobile Navbar -->
      <div class="flex md:hidden items-center justify-between px-4">
        <span class="font-bold text-xl">Newbyte</span>
        <button @click="toggleMenu" class="text-gray-700 focus:outline-none">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
          </svg>
        </button>
      </div>
  
      <!-- Mobile Menu -->
      <div
        v-if="menuOpen"
        class="fixed top-0 left-0 w-screen h-screen bg-white flex flex-col items-center justify-center space-y-6 z-40"
      >
      <span class="font-bold text-xl absolute top-6 left-4">Newbyte</span>
        <button @click="toggleMenu" class="absolute top-0 right-4 text-gray-700 focus:outline-none">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
        <a href="#" @click="toggleMenu" class="text-2xl text-gray-700 hover:text-blue-500">Home</a>
        <a href="#services" @click="toggleMenu" class="text-2xl text-gray-700 hover:text-blue-500">Services</a>
        <a href="#team" @click="toggleMenu" class="text-2xl text-gray-700 hover:text-blue-500">Team</a>
        <a href="#contact" @click="toggleMenu" class="text-2xl text-gray-700 hover:text-blue-500">Contact us</a>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    data() {
      return {
        menuOpen: false,
      };
    },
    methods: {
      toggleMenu() {
        this.menuOpen = !this.menuOpen;
      },
    },
  };
</script>