<script setup>

</script>
<template>
    <div class="min-h-screen bg-gray-100 dark:bg-gray-900">
      <!-- Header -->
      <header class="bg-white dark:bg-gray-800 shadow-md py-4">
        <div class="container mx-auto flex justify-between items-center px-4">
          <div class="text-2xl font-bold text-gray-800 dark:text-white">
            PaletteVisualizer
          </div>
          <nav>
            <ul class="flex space-x-4">
              <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:underline">Create Palette</a></li>
              <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:underline">Explore</a></li>
              <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:underline">Sign In</a></li>
            </ul>
          </nav>
        </div>
      </header>
  
      <!-- Hero Section -->
      <section class="text-center py-16 bg-white dark:bg-gray-800">
        <div class="container mx-auto px-4">
          <h1 class="text-4xl font-extrabold text-gray-800 dark:text-white">Create and Visualize Stunning Color Palettes</h1>
          <p class="text-lg mt-4 text-gray-600 dark:text-gray-300">
            Design color palettes and see how they’ll look in your mobile app instantly.
          </p>
          <button class="mt-8 px-6 py-3 bg-blue-600 text-white rounded-lg hover:bg-blue-700">
            Get Started
          </button>
          <!-- Illustration/Image -->
          <div class="mt-12">
            <img src="/mockup.png" alt="App Mockup" class="mx-auto max-w-lg rounded-lg shadow-lg">
          </div>
        </div>
      </section>
  
      <!-- Feature Highlights -->
      <section class="py-16 bg-gray-100 dark:bg-gray-900">
        <div class="container mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
            <h3 class="text-2xl font-bold text-gray-800 dark:text-white">Palette Editor</h3>
            <p class="mt-4 text-gray-600 dark:text-gray-300">Easily pick and adjust colors to create your perfect palette.</p>
          </div>
          <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
            <h3 class="text-2xl font-bold text-gray-800 dark:text-white">Real-Time Visualization</h3>
            <p class="mt-4 text-gray-600 dark:text-gray-300">See changes instantly as you modify your palette.</p>
          </div>
          <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
            <h3 class="text-2xl font-bold text-gray-800 dark:text-white">Accessibility Checks</h3>
            <p class="mt-4 text-gray-600 dark:text-gray-300">Ensure your color choices are accessible to everyone.</p>
          </div>
        </div>
      </section>
  
      <!-- Popular Palettes -->
      <section class="py-16 bg-white dark:bg-gray-800">
        <div class="container mx-auto px-4">
          <h2 class="text-3xl font-bold text-gray-800 dark:text-white text-center">Popular Palettes</h2>
          <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Example Palette Card -->
            <div class="bg-gray-100 dark:bg-gray-900 p-6 rounded-lg shadow-md">
              <div class="flex space-x-2 mb-4">
                <div class="w-10 h-10 bg-blue-500 rounded"></div>
                <div class="w-10 h-10 bg-green-500 rounded"></div>
                <div class="w-10 h-10 bg-red-500 rounded"></div>
              </div>
              <button class="px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700">View Palette</button>
            </div>
            <!-- Repeat for more palettes -->
          </div>
          <div class="mt-8 text-center">
            <button class="px-6 py-3 bg-blue-600 text-white rounded-lg hover:bg-blue-700">Load More</button>
          </div>
        </div>
      </section>
  
      <!-- Footer -->
      <footer class="bg-gray-800 text-gray-300 py-6">
        <div class="container mx-auto px-4 text-center">
          <p>&copy; 2024 PaletteVisualizer. All rights reserved.</p>
          <div class="mt-4">
            <a href="#" class="hover:underline">Privacy Policy</a> | 
            <a href="#" class="hover:underline">Terms of Service</a>
          </div>
        </div>
      </footer>
    </div>
  </template>
