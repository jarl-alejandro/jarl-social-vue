<template lang="pug">
  #app
    h1 Hola Mundo
    button.button.is-primary.is-large Button
    jc-form
</template>

<script>
import JcForm from '@/components/chat/Form.vue'

export default {
  name: 'app',
  components:  {
    JcForm
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
@import './scss/style.scss';

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
