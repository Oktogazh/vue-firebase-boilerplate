<template>
    <AppNavbar />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import AppNavbar from './components/AppNavbar.vue'

export default defineComponent({
  name: 'App',
  components: {
    AppNavbar,
  },
})
</script>


<style scoped>
</style>
