<template>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Projetos</a></li>
    <li><a href="#">Contato</a></li>
    <li v-if = "esta_logado"><a href = "#" > Meu Perfil </a></li>
  </ul>
</template>

<script>
  export default {
    name: 'Header',
    props: ["esta_logado"]
  }
</script>

<style scoped>
  ul {
    list-style: none;
    display: flex;
  }
  li {
    margin-right: 10px;
  }
  a {
    color: rgb(6, 100, 72);
    text-decoration: none;
    transition: .5s;
  }
  a:hover {
    color: rgb(38, 61, 192);
  }
</style>
© 2021 GitHub, Inc.