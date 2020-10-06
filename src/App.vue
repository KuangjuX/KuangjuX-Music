<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <router-view></router-view>
  </div>
</template>

<style lang="stylus">
</style>

<script>
import MHeader from './components/m-header/m-header'
import Tab from './components/tab/tab'

export default {
  components:{
    MHeader,
    Tab
  }
}
</script>
