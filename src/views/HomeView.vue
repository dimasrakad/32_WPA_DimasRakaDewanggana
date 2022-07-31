<template>
  <div class="home">
    <BannerComponent></BannerComponent>
    <AboutComponent></AboutComponent>
    <ServicesComponent></ServicesComponent>
    <ProjectsComponent></ProjectsComponent>
    <TestimonialsComponent></TestimonialsComponent>
  </div>
</template>

<script>
// @ is an alias to /src
import BannerComponent from '@/components/Home/BannerComponent.vue'
import AboutComponent from '../components/Home/AboutComponent.vue'
import TestimonialsComponent from '../components/Home/TestimonialsComponent.vue'
import ProjectsComponent from '@/components/Home/ProjectsComponent.vue'
import ServicesComponent from '@/components/Home/ServicesComponent.vue'

export default {
  name: 'HomeView',
  components: {
    BannerComponent,
    AboutComponent,
    TestimonialsComponent,
    ProjectsComponent,
    ServicesComponent
}
}
</script>
