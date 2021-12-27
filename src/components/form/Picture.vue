<template>
<div>
    <img :src="usuario_padrão" :alt="descricao">
    <MudarImagem @mudar-imagem="trocarImagem" />
</div>
</template>

<script>

import MudarImagem from './MudarImagem.vue'
    
export default {
    name: 'Picture',
    components: {
            Reutilizacao,
            MudarImagem
    },
    data() {
        return {
            usuario_padrão: "/img/usuario_padrão.png",
            descricao: "Usuário Padrão"

        },
        
    methods: {
        trocarImagem() {
            console.log("Opa")
            }
    
        }
    }
}
</script>
