<script setup>
import MenuComponents from './components/MenuComponents.vue'
import HomeView from './view/HomeView.vue'
import AboutView from './view/AboutView.vue'
import TimeView from './view/TimeView.vue'
import TrainingView from './view/TrainingView.vue'
import HealthCoachView from './view/HealthCoachView.vue'
import TestimonialsView from './view/TestimonialsView.vue'
import ContactView from './view/ContactView.vue'
import FooterComponents from './components/FooterComponents.vue'
</script>

<template>
  <header>
    <MenuComponents />
    <HomeView />
    <AboutView />
    <TimeView />
    <TrainingView />
    <HealthCoachView />
    <TestimonialsView />
    <ContactView />
    <FooterComponents />
  </header>
</template>
