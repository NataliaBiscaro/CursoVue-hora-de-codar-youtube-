<template>
<div>
    <h1> Componente Dois </h1>
    <p> está {{ status }} . </p>
    <PrimeiroComponente/>
</div>
</template>

<script>

    import PrimeiroComponente from './PrimeiroComponente.vue';
    export default{
        
        name: 'SegundoComponenteTeste',
        components: {
            PrimeiroComponente
        },
        data() {
            return{
              status: 'funcionando'
            }
        }
    }
</script>
