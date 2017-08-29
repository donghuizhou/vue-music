<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <player></player>
  </div>
</template>

<script>
import MHeader from 'components/m-header/m-header'
import Tab from 'components/tab/tab'
import Player from 'components/player/player.vue'

export default {
  date() { },
  methods: {},
  mounted() { },
  components: {
    MHeader,
    Tab,
    Player
  }
}
</script>

<style lang="stylus">
</style>
