<script>
export default {
  data() {
    return {
      title: 'Projects'
    }
  }
}
</script>

<template>
  <section class="max-w-8l mx-auto w-5/6 max-md:w-full px-6 sm:px-6">
    <h2 class="font-bold text-3xl">{{ title }}</h2>

    <div
      class="p-10 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5"
    >
      <!--Card 1-->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="w-full" src="../assets/Projects/Text_to_speech.png" alt="Mountain" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Text to Speech Application</div>
          <p class="text-gray-700 text-base">
            My final year project was a web based text to speech application. Utilizing the web
            speech api integrating SpeechSynthesis and SpeechRecognition.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vue JS</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >TailwindCSS</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Web Speech API</span
          >
        </div>
      </div>
      <!--Card 2-->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="w-full" src="../assets/Projects/Jacks_Pets.png" alt="Jacks pet shop" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Jacks Pet Shop</div>
          <p class="text-gray-700 text-base">
            Web Development assignment whilst in my final year of university, creating a e-commerce
            website using a front-end frame.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vue JS</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Firebase</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >TailwindCSS</span
          >
        </div>
      </div>

      <!--Card 3-->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="w-full" src="/forest.jpg" alt="Forest" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Forest</div>
          <p class="text-gray-700 text-base">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, Nonea!
            Maiores et perferendis eaque, exercitationem praesentium nihil.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >#photography</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >#travel</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >#fall</span
          >
        </div>
      </div>
    </div>
  </section>
</template>
