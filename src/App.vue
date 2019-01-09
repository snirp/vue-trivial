<template>
  <div id="app">
    <trivial-component msg="This is the trivial component"/>
    <trivial-component msg="And again"/>
  </div>
</template>

<script>
import TrivialComponent from './TrivialComponent.vue'

export default {
  name: 'app',
  components: {
    TrivialComponent
  }
}
</script>

