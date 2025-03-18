<template>
  <div class="bg-white p-8 rounded-lg shadow-xl mb-8">
    <h2 class="text-3xl font-bold text-indigo-600 mb-6">Capstone Project</h2>
    <p class="mb-2 text-gray-800"><strong>Project Summary:</strong> <a :href="projectSummary" download class="text-blue-500 underline ml-2">Download Project Summary</a></p>
    <p class="mb-2 text-gray-800"><strong>Project Vision:</strong> <a :href="projectVision" download class="text-blue-500 underline ml-2">Download Project Vision</a></p>
    <p class="mb-2 text-gray-800"><strong>High Level Requirements:</strong> <a download class="text-blue-500 underline ml-2" :href="highLevelRequirements">Download High Level Requirements</a> </p>
    <p class="mb-2 text-gray-800"><strong>Project Plan:</strong> <a :href="projectPlanPdf" download class="text-blue-500 underline ml-2">Download Project Plan</a></p>
    <p class="mb-2 text-gray-800"><strong>Requirements Analysis and Design:</strong> <a :href="requirementsAnalysisAndDesign" download class="text-blue-500 underline ml-2">Download Requirements Analysis And Design</a></p>
    <p class="mb-2 text-gray-800"><strong>Wireframes/Mockups:</strong> <a href="https://www.figma.com/design/BYvxgaOFLVdm9RrjR3SqKl/Opportune-Mockup?node-id=0-1&t=ZYI6FnGgBhypWzhA-1" class="text-blue-500 underline ml-2">Open Figma Design</a></p>
    <p class="mb-2 text-gray-800"><strong>System Implementation:</strong> Work in progress</p>
  </div>
</template>

<script>
import projectPlanPdf from '../assets/project_plan.pdf';
import requirementsAnalysisAndDesign from '../assets/requirements_analysis_and_design.pdf';
import projectVision from '../assets/project_vision.pdf';
import highLevelRequirements from '../assets/high_level_requirements.pdf';
import projectSummary from '../assets/project_summary.pdf';

export default {
  name: 'CapstoneProject',
  data() {
    return {
      projectPlanPdf,
      projectVision,
      requirementsAnalysisAndDesign,
      projectSummary,
      highLevelRequirements
    }
  }
}
</script>
