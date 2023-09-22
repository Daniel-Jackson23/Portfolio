<template>
  <nav
    class="w-5/6 max-md:w-full relative flex flex-wrap items-center justify-between bg-white-500 mb-3 container px-6 py-4 mx-auto md:flex md:justify-between md:items-center"
  >
    <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
      <div
        class="w-full relative flex justify-between lg:w-auto px-4 lg:static lg:block lg:justify-start"
      >
        <a
          class="text-sm font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercase text-black"
          href="#pablo"
        >
          Daniel Jackson
        </a>
        <button
          class="text-black cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          v-on:click="toggleNavbar()"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6"
          >
            <path
              stroke-linecap="round"  
              stroke-linejoin="round"
              d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
            />
          </svg>
        </button>
      </div>
      <div
        v-bind:class="{ hidden: !showMenu, flex: showMenu }"
        class="lg:flex lg:flex-grow items-center"
      >
        <ul class="flex flex-col lg:flex-row list-none ml-auto">
          <li class="nav-item">
            <router-link
              to="/"
              class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-black hover:opacity-75"
              href="#pablo"
            >
              <i class="text-lg leading-lg text-white opacity-75" /><span class="ml-2">Home</span>
            </router-link>
          </li>
          <li class="nav-item">
            <router-link
              to="/about"
              class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-black hover:opacity-75"
              href="#pablo"
            >
              <i class="text-lg leading-lg text-white opacity-75" /><span class="ml-2"
                >About me</span
              >
            </router-link>
          </li>
          <li class="nav-item">
            <router-link
              to="/work"
              class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug text-black hover:opacity-75"
              href="#pablo"
            >
              <i class="text-lg leading-lg text-white opacity-75" /><span class="ml-2"
                >Projects</span
              >
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'navBar',
  data() {
    return {
      showMenu: false
    }
  },
  methods: {
    toggleNavbar: function () {
      this.showMenu = !this.showMenu
    }
  }
}
</script>
