<script>
export default {
  data() {
    return {
      name: 'Daniel Jackson',
      jobTitle: 'Front-end developer'
    }
  },
  methods: {
    sendTo() {
      window.open = 'mailto:danieljackson104@googlemail.com'
    }
  },
  mounted() {
    this.sendTo()
  }
}
</script>

<template>
  <section class="max-w-8l mx-auto w-5/6 max-md:w-full px-6 sm:px-6">
    <div class="flex justify-center flex-row max-sm:flex-col">
      <div class="relative w-2/4 max-sm:w-full">
        <h1 class="font-bold text-4xl py-10">Welcome!!</h1>
        <p>
          My name is <span class="font-bold">{{ name }}</span> I'm
          <span class="font-bold">{{ jobTitle }}</span
          >. I build web applications, designing websites and mobile apps I have
          recently graduated University with a BSC in Computer Science. My final year project was a
          web based text to speech application for students with dyslexia.
        </p>
        <div class="flex py-8">
          <a
            type="button"
            :on-click="sendTo()"
            role="button"
            href="mailto:danieljackson104@googlemail.com"
            class="py-2.5 px-5 mr-2 mb-2 text-sm font-medium text-gray-100 focus:outline-none bg-white rounded-lg border border-gray-200 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-100 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700"
            >Contact me</a
          >
          <a
            href="https://www.linkedin.com/in/daniel-jackson-044b3b194/"
            type="button"
            class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
            >LinkedIn</a
          >
        </div>
      </div>
      <img src="../assets/main-image.jpg" alt="web dev" class="rounded pl-0.5" />
    </div>
  </section>
</template>
