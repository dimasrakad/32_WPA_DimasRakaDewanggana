<template>
  <div class="about">
    <AboutUsComponent></AboutUsComponent>
    <VisionMissionComponent></VisionMissionComponent>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutUsComponent from '../components/About/AboutUsComponent.vue'
import VisionMissionComponent from '../components/About/VisionMissionComponent.vue'

export default {
  name: 'AboutView',
  components: {
    AboutUsComponent,
    VisionMissionComponent
}
}
</script>