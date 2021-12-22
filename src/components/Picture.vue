<template>
    <img :src="usuario_padrão" :alt="descricao">
</template>

<script>
    export default {
        name: 'Picture',
        data() {
            return{
                usuario_padrão: "/img/usuario_padrão.png",
                descricao: "Usuário Padrão"
            }
        }
    }

</script>
