<template>
  <AppHeader />
  <div class="bg-neutral-100 md:pl-24 md:pr-24 pl-3 pr-3 pb-24">
    <router-view />
  </div>
  <AppFooter />
</template>
<script>
import AppHeader from '@/components/AppHeader.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
  name: 'ChannelsView',
  components: {
    AppHeader,
    AppFooter
  },
  setup() {
    // Composition API logic
  }
}
</script>

<style>
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  font-weight: normal;
}
</style>
