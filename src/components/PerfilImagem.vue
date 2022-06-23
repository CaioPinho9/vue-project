<template>
  <img :alt="descricao" :src="avatar">
</template>
<script>
export default {
    name: 'PerfilImagem',
    data() {
        return {
            avatar: "/img/logo.png",
            descricao: "Perfil"
        }
    }
}
</script>
