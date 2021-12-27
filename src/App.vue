<template>
 <div>
   <Header  :esta_logado="true"/>
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

  import Header from './components/form/Header.vue' ;
  import PrimeiroComponente from './components/form/PrimeiroComponente.vue';
  import SegundoComponenteNatalia from './components/form/SegundoComponente.vue';
  import LifeCycle from './components/form/LifeCycle.vue';
  import Pessoa from './components/form/Pessoa.vue'

    export default {
      name: 'App', 
      components: {
        Header,
        PrimeiroComponente,
        SegundoComponenteNatalia,
        LifeCycle,
        Pessoa
      },
        data () { 
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