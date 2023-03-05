<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <MainPage/>
  </div>
</template>

<script>

import MainPage from '../components/MainPage.vue'

export default {
  name: 'HomeView',
  components: {
	MainPage
  }
  
}
</script>
