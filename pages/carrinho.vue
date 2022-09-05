<template>
  <section class="section">
    <h1 class="title">Meu Carrinho</h1>
    <div class="table-container">
      <table class="table is-fullwidth">
        <thead>
          <tr>
            <th>Produto</th>
            <th>Valor Unitário</th>
            <th>Quantidade</th>
            <th>Valor Total</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th>Produto 1</th>
            <td>R$ 2,00</td>
            <td>
              <b-field>
                <b-numberinput controls-position="compact" v-model="number" type="is-info"></b-numberinput>
              </b-field>
            </td>
            <td>R$ 2,00</td>
          </tr>
          <tr>
            <th>Produto 2</th>
            <td>R$ 3,00</td>
            <td>
              <b-field>
                <b-numberinput controls-position="compact" v-model="number" type="is-info"></b-numberinput>
              </b-field>
            </td>
            <td>R$ 3,00</td>
          </tr>
          <tr>
            <th>Produto 3</th>
            <td>R$ 4,00</td>
            <td>
              <b-field>
                <b-numberinput controls-position="compact" v-model="number" type="is-info"></b-numberinput>
              </b-field>
            </td>
            <td>R$ 3,00</td>
          </tr>
        </tbody>
      </table>
    </div>
    <h1 class="title">Preço Total: R$ 6,00</h1>
    <b-button type="is-info">Finalizar Compra</b-button>
    <b-button type="is-info">Contunuar Comprando</b-button>
  </section>
</template>