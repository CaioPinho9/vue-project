<template>
    <div>
        <p v-if="esta_trabalhando"> Estou trabalhando</p>
        <p v-else> Não estou trabalhando</p>
        <p>Para acessar meu projeto do <a v-bind:href="meu_link" target="_blank">jogo da cobrinha</a></p>
        <PerfilImagem />
        <div>
            <button @click="showEmail">{{texto_botao}}</button>
        </div>
        <p v-show="mostrar_email">Email: caiopinho9@gmail.com</p>
    </div>
</template>
<script>
    import PerfilImagem from './PerfilImagem.vue'

    export default {
        name: "InfoTest",
        components: {
            PerfilImagem
        },
        data() {
            return {
                esta_trabalhando: false,
                mostrar_email: false,
                meu_link: 'https://caiopinho9.github.io/snake-game/',
                texto_botao: "Mostrar email"
            }
        },
        methods: {
            showEmail() {
                this.mostrar_email = !this.mostrar_email
                if (!this.mostrar_email) {
                    this.texto_botao = "Mostrar email"
                } else {
                    this.texto_botao = "Esconder email"
                }
            }
        }
    }
</script>