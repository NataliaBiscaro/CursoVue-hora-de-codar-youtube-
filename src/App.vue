<template>
 <div>
    <PrimeiroComponente/>
    <SegundoComponente/>
    <Life-cycle/>
    <Pessoa/>
    <p> {{ dado }} </p>
 </div>
</template>

<script>

  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import SegundoComponente from './components/SegundoComponente.vue';
  import LifeCycle from './components/LifeCycle.vue';
  import Pessoa from './components/Pessoa.vue'

    export default {
      name: 'App', 
      components: {
        PrimeiroComponente,
        SegundoComponente,
        LifeCycle,
        Pessoa
      },
            LifeCycledata() {
        return {
          dado: "testanduuuu"
        }
      } 
    }
</script>