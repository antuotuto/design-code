<template>
  <div id="app">
    <hello :an="yao"></hello>
  </div>
</template>

<script>
import hello from '@/components/Hello'

export default {
  name: 'app',
  data () {
    return{
      yao:'2'
    }
  },
  components: {
      hello
  }
}
</script>

<style lang="scss">
#app {
  // font-family: 'Avenir', Helvetica, Arial, sans-serif;
  font-family: -apple-system, BlinkMacSystemFont,
    "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell",
    "Fira Sans", "Droid Sans", "Helvetica Neue",
    sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height:100%;
  width:100%;
  button{
    outline: none;
  }
}



</style>
