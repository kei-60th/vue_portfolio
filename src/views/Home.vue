<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <page1 msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import page1 from '@/components/page1.vue'

export default {
  name: 'home',
  components: {
    page1
  }
}
</script>

