<script>
import HomeBanner from '../components/HomeBanner.vue'
import Experience from '../components/ExperienceSection.vue'
import TechStack from '../components/TechStack.vue'

export default {
  data() {
    return {}
  },
  components: {
    HomeBanner,
    Experience,
    TechStack
  }
}
</script>

<template class="container px-5 py-3 mx-auto flex flex-row sm:max-lg:flex-col">
  <main>
    <HomeBanner />
    <Experience />
    <TechStack />
  </main>
</template>
