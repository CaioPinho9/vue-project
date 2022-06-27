<template>
    <div>
        <form action="" @submit="enviarFormulario($event)">
            <input type="text" placeholder="nome" v-model="name"><br>
            <input type="text" placeholder="email" v-model="email"><br>
            <input type="submit" value="Enviar">
    </form>
    </div>
</template>

<script>
export default {
    name: 'FormNameEmail',
    data() {
        return {
            name: "",
            email: ""
        }
    },
    methods: {
        enviarFormulario(e) {

            e.preventDefault()

            const name = this.name
            const email = this.email

            console.log("Formulario Enviado");
            console.log("Nome é " + name);
            console.log("Email é " + email);
        }
    }
}
</script>

<style scoped>
    input {
        margin: 3px;
    }
</style>