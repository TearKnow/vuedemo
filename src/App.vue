<template>
  <div id="app">
    <HelloWorld msg="1.父组件里的信息，通过props传给子组件使用"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {

}
</style>
