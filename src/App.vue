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
  margin-top: 0px;
  background-color: #1b2841;
}

ul {
    list-style: none;
    padding: 0;
}

li {
    margin-left: 10px;
    margin-right: 10px;
}

a {
  color: #1496de;
}
</style>
