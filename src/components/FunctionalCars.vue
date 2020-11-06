<template functional>
  <div>
    <!-- <p v-for="car in props.cars" :key="car">{{car}}</p> -->
    <ul v-for="car in props.cars" :key="car">
      <li>{{car}}</li>
    </ul>
  </div>
</template>

<script> 
export default {
  functional: true,
  name: 'functionalCars',
  props: {
    cars: Array
  }
}
</script>