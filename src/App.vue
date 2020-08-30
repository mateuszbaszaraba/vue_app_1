<template>
  <div class="container">
    <app-header></app-header>
    <router-view></router-view>
  </div>
</template>

<script>
import header from '@/components/Header.vue'

export default {
  components: {
    appHeader: header
  }
}
</script>
