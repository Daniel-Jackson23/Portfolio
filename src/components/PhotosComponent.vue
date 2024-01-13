<script>
export default {
  name: 'PhotosComponent',
  components: {},
  props: {
    image: String,
    id: Number
  }
}
</script>

<template class="">
  <section>
    <div>
      <img class="h-auto max-w-full rounded-lg" :src="image" alt="" width="500" height="500" />
    </div>
  </section>
</template>
