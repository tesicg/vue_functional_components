<template>
  <div id="app">
    <FunctionalCars
     :cars = "['BMW', 'Volvo', 'Opel', 'Audi']"
    />
  </div>
</template>

<script>
import FunctionalCars from './components/FunctionalCars.vue'

export default {
  name: 'app',
  components: {
    FunctionalCars
  }
}
</script>

<style scoped>
</style>