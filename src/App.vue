<template>
  <div id="app">
    {{ a }}
    <button @click="test">click</button>
    <router-view />
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'
@Component
export default class App extends Vue {
  a = '1'
  test() {
    console.log('abc')
  }

  created() {
    console.log(9969)
  }
}
</script>
<style lang="scss" scoped></style>
