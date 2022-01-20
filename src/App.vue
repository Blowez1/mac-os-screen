<template>
  <div id="app">
    <Header/>
    <main>
     <Tab/>
    </main>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Tab from './components/Tab.vue'

export default {
  name: 'App',
  components : {
      Header, Tab
  }
}
</script>
<style lang="scss">
@import './assets/scss/main.scss';
</style>
