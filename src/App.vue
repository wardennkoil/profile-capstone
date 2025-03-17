<template>
  <div>
    <NavBar />
    <main class="container mx-auto p-4">
      <section id="personal-data" class="mb-12">
        <PersonalData />
      </section>
      <section id="academic-credentials" class="mb-12">
        <AcademicCredentials />
      </section>
      <section id="academic-work" class="mb-12">
        <AcademicWork />
      </section>
      <section id="capstone-project" class="mb-12">
        <CapstoneProject />
      </section>
      <section id="professional-summary" class="mb-12">
        <ProfessionalSummary />
      </section>
    </main>
    <Footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'
import PersonalData from './components/PersonalData.vue'
import AcademicCredentials from './components/AcademicCredentials.vue'
import AcademicWork from './components/AcademicWork.vue'
import CapstoneProject from './components/CapstoneProject.vue'
import ProfessionalSummary from './components/ProfessionalSummary.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Footer,
    PersonalData,
    AcademicCredentials,
    AcademicWork,
    CapstoneProject,
    ProfessionalSummary
  }
}
</script>
