<template>
  <HeaderPage />
  <FirstComponent />
  <InfoTest />
</template>

<script>
import HeaderPage from './components/HeaderPage.vue'
import FirstComponent from './components/FirstComponent.vue'
import InfoTest from './components/InfoTest.vue'

export default {
  name: 'App',
  components: {
    FirstComponent,
    InfoTest,
    HeaderPage
  }
}
</script>

<style>
body {
 font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
  background-color: #1b2841;
}

a {
  color: #1496de;
}
</style>
