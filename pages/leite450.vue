<template>
 <section>
   <div class="columns">
      <div class="column is-3">
        <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/leite-fermentado-450.png">
        </figure>
      </div>
      <div class="column is-6">
        <article class="notification is-info">
         <p class="title">Leite Fermentado 450 ml</p>
        </article>
        <article class="notification is-info">
         <p class="subtitle">Tipo yakult com 450 ml</p>
        </article>
      </div>
      <div class="column is-3">
        <article class="notification is-info">
         <p class="title">12 bolsocoins</p>
         <p>Quantidade:</p>
        </article>
        <b-field>
         <b-numberinput v-model="number"></b-numberinput>
        </b-field>
        <b-button type="is-info">Adicionar ao carrinho</b-button>
      </div>
    </div>
   <div>
    <article class="notification is-info">
     <p class="subtitle">450 ml de leite fermentado</p>
    </article>
   </div>
   <br>
   <div>
    <article class="notification is-info">
     <p class="subtitle">Comentários:</p>
     <br>
     <p class="subtitle">Clébinho: Parece yakult!</p>
     <p class="subtitle">João: Chamyto + lactobacilos!</p>
    </article>
   </div>
   <br><br>
   <h1 class="title">Produtos Relacionados:</h1>
    <div class="columns mt-5">
      <div class="column is-3">
        <figure class="image is-300x300">
  <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/chamyto-1-1.png">
        </figure>
        <article class="notification is-info">
          <p class="title">Chamyto 1+1</p>
          <p class="subtitle">5 bolsocoins</p>
          <router-link :to="{ path: '/chamyto1' }">Mais informações</router-link>
        </article>
      </div>
      <div class="column is-3">
        <figure class="image is-300x300">
  <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/iogurte-100g.png">
        </figure>
        <article class="notification is-info">
          <p class="title">Iogurte 100g</p>
          <p class="subtitle">10 bolsocions</p>
          <router-link :to="{ path: '/iogurte' }">Mais informações</router-link>
        </article>
      </div> 
      <div class="column is-3">
        <figure class="image is-300x300">
  <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/leite-fermentado-450.png">
        </figure>
        <article class="notification is-info">
          <p class="title">Leite fermentado 450g</p>
          <p class="subtitle">12 bolsocoins</p>
          <router-link :to="{ path: '/leite450' }">Mais informações</router-link>
        </article>
      </div>     
      <div class="column is-3">
        <figure class="image is-300x300">
  <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/leite-fermentado-720g.png">
        </figure>
        <article class="notification is-info">
          <p class="title">Leite fermentado 720g</p>
          <p class="subtitle">15 bolsocoins</p>
          <router-link :to="{ path: '/leite720' }">Mais informações</router-link>
        </article>
      </div>     
    </div>
 </section>
</template>