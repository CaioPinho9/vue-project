<template>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Projetos</a></li>
        <li><a href="#">Contato</a></li>
    </ul>
</template>
<script>
export default {
    name: "HeaderPage"
}
</script>

<style scoped>

ul {
    list-style: none;
    display: inline-flex;
    padding: 0;
}

li {
    margin-left: 10px;
    margin-right: 10px;
}

a {
    text-decoration: none;
    transition: .5s;
}

a:hover {
    color: #19afff;
}

</style>