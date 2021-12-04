<template>
<div>
    <h1> Componente Dois </h1>
    <p> está {{ status }} . </p>
</div>

</template>

<script>
    export default{
        name: 'SegundoComponente',
        data() {
            return{
              status: 'funcionando'
            }
        }
    }
</script>
