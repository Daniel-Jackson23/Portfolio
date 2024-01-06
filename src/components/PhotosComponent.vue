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

<template>
  <section class="max-w-8l mx-auto w-5/6 max-md:w-full px-6 sm:px-6">
    <div>
      <img class="h-auto max-w-full rounded-lg" :src="image" alt="" sizes="" srcset="" />
    </div>
  </section>
</template>
