<script>
import AboutMeComponent from '../components/AboutMeComponent.vue'
import PhotosComponent from '../components/PhotosComponent.vue'
import json from '../assets/JsonData/PhotoData.json'

export default {
  data() {
    return {
      photos: json
    }
  },
  components: {
    AboutMeComponent,
    // PhotosComponent
  }
}
</script>

<template class="container px-5 py-3 mx-auto flex flex-row sm:max-lg:flex-col">
  <div >
    <AboutMeComponent />
  </div>
  <!-- <div class="max-w-8l mx-auto w-5/6 max-md:w-full px-6 sm:px-6">
    <h2 class="font-bold text-3xl py-5">Photos I've taken</h2>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-1">
      <PhotosComponent class="" v-for="photo in photos" :key="photo.id" :image="photo.image" />
    </div>
  </div> -->
</template>
