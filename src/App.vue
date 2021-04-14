<template>
  <div id="app">
    <div class="text">hello</div>
    <router-view />
  </div>
</template>
<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'App',
  data() {
    return {
      a: 123
    }
  }
})
</script>
<style lang="scss" scoped>
.text {
  color: $success-color;
}
</style>
