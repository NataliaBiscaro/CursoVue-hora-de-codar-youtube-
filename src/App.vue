<template>
 <div>
    <PrimeiroComponente/>
    <SegundoComponente/>
    <Life-cycle/>
    <p> {{ dado }} </p>
 </div>
</template>

<script>

  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import SegundoComponente from './components/SegundoComponente.vue';
  import LifeCycle from './components/LifeCycle.vue'

    export default {
      name: 'App', 
      components: {
        PrimeiroComponente,
        SegundoComponente,
        LifeCycle
      },
            LifeCycledata() {
        return {
          dado: "testanduuuu"
        }
      } 
    }
</script>