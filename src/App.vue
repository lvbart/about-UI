<template>
  <div id="app">
    
    <SignInForm/>
  </div>
</template>

<script>
import SignInForm from './components/SignInForm.vue'

export default {
  name: 'App',
  components: {
    SignInForm
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
