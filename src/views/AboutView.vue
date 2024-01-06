<script>
import AboutMeComponent from '../components/AboutMeComponent.vue'
import PhotosComponent from '../components/PhotosComponent.vue';
import json from '../assets/JsonData/PhotoData.json'

export default {
  data() {
    return {
      photos: json
    }
  },
  components: {
    AboutMeComponent,
    PhotosComponent
  }
}
</script>

<template class="container px-5 py-3 mx-auto flex flex-row sm:max-lg:flex-col">
  <div>
    <AboutMeComponent />  
  </div>
  <div class="grid grid-cols-2 md:grid-cols-3 gap-2">
    <PhotosComponent class=""  v-for="photo in photos" :key="photo.id" :image="photo.image" />
  </div>
</template>

