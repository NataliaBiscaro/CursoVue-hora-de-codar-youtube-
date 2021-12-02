<template>
<div>
    <h1> Esse eu fiz sozinha :) </h1>
    <p> Eu me sinto {{ status }} . </p>
</div>

</template>

<script>
    export default{
        name: 'SegundoComponente',
        data() {
            return{
              status: 'feliz por estar evoluindo'
            }
        }
    }
</script>
