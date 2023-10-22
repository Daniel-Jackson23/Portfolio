<script>
export default {
  data() {
    return {
      Title: 'Technolgies I Use'
    }
  }
}
</script>

<template>
  <section class="flex flex-col max-w-8l mx-auto px-6 sm:px-6 w-5/6 max-md:w-full">
    <div class="flex-row maz-sm:flex-col">
      <h2 class="text-2xl font-bold text-center p-4">{{ Title }}</h2>
    </div>

    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      <div class="grid gap-4">
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/angular.png" alt="" />
        </div>
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/aspnet.png" alt="" />
        </div>
        <div>
          <img class="h-auto max-w-full rounded-lg" src="" alt="" />
        </div>
      </div>
      <div class="grid gap-4">
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/sass.png" alt="" />
        </div>
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/JavaScript.png" alt="" />
        </div>
       
      </div>
      <div class="grid gap-4">
        <div>
          <img
            class="h-auto max-w-full rounded-lg p-2"
            src="../assets/logos/react-1-logo-png-transparent.png"
            alt=""
          />
        </div>
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/csharpe.png" alt="" />
        </div>
      </div>
      <div class="grid gap-4">
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/Vue.png" alt="" />
        </div>
        <div>
          <img class="h-auto max-w-full rounded-lg" src="../assets/logos/tailwind.png" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>
