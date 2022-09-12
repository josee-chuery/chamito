<template>
  <section class="section">
    <h1 class="title">Meu Carrinho</h1>
    <div class="table-container">
      <table class="table is-fullwidth">
        <thead>
          <tr>
            <th>Produto</th>
            <th>Quantidade</th>
            <th>Valor Unitário</th>
            <th>Valor Total</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="produto in produtos" :key="produto.nome">
            <td>{{produto.nome}}</td>
            <td>
              <b-field>
                <b-numberinput controls-position="compact" v-model="quantidade1" type="is-info"></b-numberinput>
              </b-field>
            </td>
            <td>{{produto.nome}}</td>
          </tr>
        </tbody>
      </table>
    </div>
    <h1 class="title">Preço Total: R$ {{resultado}}</h1>
    <b-button type="is-info">Finalizar Compra</b-button>
    <b-button type="is-info">Contunuar Comprando</b-button>
  </section>
</template>
<script>
export default {
    data() {
        return {
            mensagem: "0.00",

            produtos: [
              {
                nome: "produto1",
                valor: 2.00,
                quantidade: 1
              },
              {
                nome: "produto2",
                valor: 3.00,
                quantidade: 1
              },
              {
                nome: "produto3",
                valor: 4.00,
                quantidade: 1
              }
            ]
        }
    },
    methods: {
        teste (){
            this.mensagem = "Novo número";
        }
    }
}
</script>