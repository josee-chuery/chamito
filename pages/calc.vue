<template>
    <div>
        <h1 class="title">
            {{mensagem}}
        </h1>
        <br><br>
        <b-field label="Número 1">
            <b-input v-model="numero1"></b-input>
        </b-field>
        <b-field label="Número 2">
            <b-input v-model="numero2"></b-input>
        </b-field>
        <b-button type="is-info" @click="soma()">
            +
        </b-button>
        <b-button type="is-info" @click="menos()">
            -
        </b-button>
        <b-button type="is-info" @click="multi()">
            *
        </b-button>
        <b-button type="is-info" @click="divisao()">
            /
        </b-button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            mensagem: "R$ 0,00",
            numero1: 0,
            numero2: 0,
            resultado: 0
        }
    },
    methods: {
        teste (){
            this.mensagem = "Novo número";
        },
        soma (){
            this.mensagem = parseInt(this.numero1) + parseInt(this.numero2);
        },
        menos (){
            this.mensagem = parseInt(this.numero1) - parseInt(this.numero2);
        },
        multi (){
            this.mensagem = parseInt(this.numero1) * parseInt(this.numero2);
        },
        divisao (){
            this.mensagem = parseInt(this.numero1) / parseInt(this.numero2)
        }
    }
}
</script>