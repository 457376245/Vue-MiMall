<template>
  <div class="home">
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import NavFooter from './Nav-Footer.vue'
import NavHeader from './Nav-Header.vue'
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
    NavHeader,
    NavFooter
    
  }
}
</script>
