 <script setup>
  import {defineAsyncComponent} from 'vue'

  const NavBar = defineAsyncComponent(() =>import('./components/NavBar.vue'))
  const HeroSection = defineAsyncComponent(() =>import('./components/HeroSection.vue'))
  const ServicesSection = defineAsyncComponent(() =>import('./components/ServicesSection.vue'))
  const AboutSection = defineAsyncComponent(() =>import('./components/AboutSection.vue'))
  const ExperienceAndSkills = defineAsyncComponent(() =>import('./components/ExperienceAndSkills.vue'))
  const ContactSection = defineAsyncComponent(() =>import('./components/ContactSection.vue'))
  const TestimonialsSection = defineAsyncComponent(() =>import('./components/TestimonialsSection.vue'))
</script>

<template>
    <div class="bg-[#111827] min-h-screen">
      <NavBar />
      <HeroSection />
      <ServicesSection />
      <AboutSection />
      <ExperienceAndSkills />
      <ContactSection />
      <TestimonialsSection />
    </div>
</template>


