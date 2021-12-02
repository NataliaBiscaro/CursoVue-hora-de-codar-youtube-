<template>
 <div>
    <PrimeiroComponente />
    <SegundoComponente/>
    <p> {{ dado }} </p>
 </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import SegundoComponente from './components/SegundoComponente.vue'

    export default {
      name: 'App', 
      components: {
        PrimeiroComponente,
        SegundoComponente,
      },
      data() {
        return {
          dado: "testanduuuu"
        }
      } 
    }
</script>