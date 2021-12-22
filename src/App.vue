<template>
 <div>
    teste1 
    <PrimeiroComponente/>
    teste 2
    <SegundoComponenteNatalia/>
    teste 3
    <Life-cycle/>
    <Pessoa/>
    <p class="paragrafo_pai"> {{ dado }} </p>
 </div>
</template>

<script>

  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import SegundoComponenteNatalia from './components/SegundoComponente.vue';
  import LifeCycle from './components/LifeCycle.vue';
  import Pessoa from './components/Pessoa.vue'

    export default {
      name: 'App', 
      components: {
        PrimeiroComponente,
        SegundoComponenteNatalia,
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

<style>
  body {
    background-color: #b7e698;
    color: rgba(37, 117, 21, 0.699);

  }

  a {
    color: rgb(7, 54, 56);
  }

  .teste {
    background: #d7ddd4 ; 
  }
</style>

<style>
  paragrafo_pai {
    color: aqua;
  }

</style>