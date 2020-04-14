<template>
  <div id="app">
  <onetable></onetable>
  <twotable></twotable>
  </div>
</template>

<script>
import onetable from './components/onetable.vue'
import twotable from './components/twotable.vue'

export default {
  name: 'App',
  components: {
    onetable,
    twotable
  }
}
</script>

<style>

</style>
