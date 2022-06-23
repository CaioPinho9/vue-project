<template>
  <FirstComponent />
  <InfoTest />
</template>

<script>
import FirstComponent from './components/FirstComponent.vue'
import InfoTest from './components/InfoTest.vue'

export default {
  name: 'App',
  components: {
    FirstComponent,
    InfoTest
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
