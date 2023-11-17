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
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vite</span
          >
        </div>
        <div class="flex justify-normal px-6 pt-4 pb-2">
          <button
            type="button"
            class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2"
          >
            <a href="https://github.com/Daniel-Jackson23/Text-to-speech-FYP"> View Code </a>
          </button>
        </div>
      </div>
      <!--Card 2-->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="image-1 " src="../assets/Projects/Jacks_Pets.png" alt="Jacks pet shop" />
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
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vite</span
          >
        </div>
        <div class="flex justify-normal px-6 pt-4 pb-2">
          <button
            type="button"
            class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2"
          >
            <a href="https://github.com/Daniel-Jackson23/jackspet"> View Code </a>
          </button>
        </div>
      </div>

      <!--Card 3-->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="w-full" src="../assets/Projects/Svelete-todo.png" alt="To do" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Svelte ToDo list</div>
          <p class="text-gray-700 text-base">
            Part of my final year at university was to create a project with a new technology I
            choice to use Svelte JS.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Svelte</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Javascript</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >CSS</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vite</span
          >
        </div>
        <div class="flex justify-normal px-6 pt-4 pb-2">
          <button
            type="button"
            class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2"
          >
            <a href="https://github.com/Daniel-Jackson23/SvelteKit-Todos"> View Code </a>
          </button>
        </div>
      </div>

      <!-- card 4 -->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="w-full" src="../assets/Projects/vue-todo.png" alt="To do" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Vue ToDo list</div>
          <p class="text-gray-700 text-base">
            One of my final year modules (Multiple Devices and User Experiance) was to use a showcase a technology that you have
            used before by creating anything that I wanted.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vue JS</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Javascript</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >SCSS</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Vite</span
          >
        </div>
        <div class="flex justify-normal px-6 pt-4 pb-2">
          <button
            type="button"
            class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2"
          >
            <a href="https://github.com/Daniel-Jackson23/VueTodo-app"> View Code </a>
          </button>
        </div>
      </div>
      <!-- Card 5 -->
      <div class="rounded overflow-hidden shadow-lg">
        <img class="w-full" src="../assets/Projects/Bellmans.png" alt="To do" />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Bellman Ford Algorithem</div>
          <p class="text-gray-700 text-base">
            Whilst in my second year of uni part of my algorthem module was to code the Bellman Ford
            Algorithem.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Python</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Algorithem</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Data Structure</span
          >
          <span
            class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
            >Shortest link</span
          >
        </div>
        <div class="flex justify-normal px-6 pt-4 pb-2">
          <button
            type="button"
            class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2"
          >
            <a href="https://github.com/Daniel-Jackson23/Bellmans/blob/main/code.py"> View Code </a>
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.image-1 {
  width: 100%;
  height: 200px;
}
</style>
