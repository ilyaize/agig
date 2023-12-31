<template>
  <header class="bg-neutral-100 text-neutral-900 md:p-12 p-3">
    <div class="flex items-center">
      <img src="../assets/logo.png" class="h-12" alt="" />
      <h1 class="site-title text-2xl font-bold pl-4">
        <a href="https://agigenesis.vercel.com/" title="AGI Genesis" rel="home">AGI Genesis</a>
      </h1>
    </div>
    <h2 class="site-description text-sm pt-3 pb-6 text-neutral-600">
      A Discord server dedicated to the exploration and advancement of Artificial General
      Intelligence and Machine Learning.
    </h2>

    <nav class="h-8 flex items-center border-b-2 border-t-2 border-gray-300 pt-8 pb-8">
      <router-link to="/" class="text-sm text-neutral-800 hover:text-neutral-600 px-6"
        >Home</router-link
      >
      <router-link to="/channels" class="text-sm text-neutral-800 hover:text-neutral-600 px-6"
        >Channels</router-link
      >
      <router-link to="/rules" class="text-sm text-neutral-800 hover:text-neutral-600 px-6"
        >Rules</router-link
      >
      <!-- <router-link to="/resources" class="text-sm text-neutral-800 hover:text-neutral-600 px-6"
        >Resources</router-link
      > -->
    </nav>
    <img class="shadow-md md:rounded-xl mt-6" src="../assets/header-image.jpg" alt="" srcset="" />
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  setup() {
    // Composition API logic
  }
}
</script>
