<template>
  <nav class="bg-gradient-to-r from-indigo-600 to-purple-600 shadow-lg p-4 sticky top-0 z-10">
    <div class="container mx-auto flex justify-between items-center">
      <div class="text-2xl font-bold text-white flex items-center">
        <!-- Optional: Include a logo image if available -->
        <img
            src="../assets/selfie.jpg"
            alt="Logo"
            class="w-10 h-10 mr-2 rounded-full border-2 border-white"
        />
        My Portfolio
      </div>
      <div class="space-x-4">
        <a href="#personal-data" class="text-white hover:text-gray-200 transition duration-300">Personal</a>
        <a href="#academic-credentials" class="text-white hover:text-gray-200 transition duration-300">Academics</a>
        <a href="#academic-work" class="text-white hover:text-gray-200 transition duration-300">Academic Work</a>
        <a href="#capstone-project" class="text-white hover:text-gray-200 transition duration-300">Capstone</a>
        <a href="#professional-summary" class="text-white hover:text-gray-200 transition duration-300">Professional</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>
