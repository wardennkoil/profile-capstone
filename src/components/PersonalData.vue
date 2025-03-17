<template>
  <div class="bg-white p-8 rounded-lg shadow-xl mb-8">
    <h2 class="text-3xl font-bold text-indigo-600 mb-6">Personal Data & Professional Introduction</h2>
    <div class="flex flex-col md:flex-row items-start">
      <div class="w-32 h-32 mb-4 md:mb-0 md:mr-6">
        <img
            src="../assets/selfie_new.jpg"
            alt="Profile Picture"
            class="rounded-lg shadow-lg border-4 border-indigo-500"
        />
      </div>
      <div class="flex-1 text-gray-800">
        <p class="mb-2"><span class="font-semibold">Name:</span> Leonid Serebryannikov</p>
        <p class="mb-2"><span class="font-semibold">Student Id:</span> 101468805</p>
        <p class="mb-2">
          <span class="font-semibold">Bio:</span> A passionate web developer with a focus on creating stunning and responsive digital experiences.
        </p>
        <p class="mb-2">
          <span class="font-semibold">Resume:</span>
          <a :href="resumePdf" download class="text-blue-500 underline ml-2">Download Resume</a>
        </p>
        <p class="mb-2">
          <span class="font-semibold">Cover Letter:</span>
          <a :href="coverLetterPdf" download class="text-blue-500 underline ml-2">Download Cover Letter</a>
        </p>
        <p class="mb-2">
          <span class="font-semibold">Philosophy / Statement of Career Goal:</span>
          “We are the facilitators of our own creative evolution” – Bill Hicks. I believe in continuous learning and evolving by combining past experiences with future ambitions.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import resumePdf from '../assets/resume.pdf'
import coverLetterPdf from '../assets/cover_letter.pdf'

export default {
  name: 'PersonalData',
  data() {
    return {
      resumePdf,
      coverLetterPdf
    }
  }
}
</script>