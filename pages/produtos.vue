<template>
  <div class="columns">
    <br>
    <div class="column is-3">
      <h1>Filtros:</h1>
      <br>
      <p> Categorias:</p>
      <br>
      <b-field>
        <b-checkbox>Iogurte</b-checkbox>
      </b-field>
      <b-field>
        <b-checkbox>Leite Fermentado</b-checkbox>
      </b-field>
      <b-field>
        <b-checkbox>Chamyto</b-checkbox>
      </b-field>
      <br>
      <p> Marcas:</p>
      <br>
      <b-field>
        <b-checkbox>Nestle</b-checkbox>
      </b-field>
      <b-field>
        <b-checkbox>Nestle</b-checkbox>
      </b-field>
      <b-field>
        <b-checkbox>Nestle</b-checkbox>
      </b-field>
    </div>
    <div class="column is-9">
      <div class="columns">
        <div class="column">
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/chamyto-1-1.png">
          </figure>
          <article class="notification is-primary">
            <p class="title">Chamyto 1+1</p>
            <p class="subtitle">5 bolsocoins</p>
            <router-link :to="{ path: '/chamyto1' }">Chamyto 1+1</router-link>
          </article>
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/chamyto-1-1.png">
          </figure>
          <article class="notification is-primary">
            <p class="title">Chamyto 1+1</p>
            <p class="subtitle">5 bolsocoins</p>
            <router-link :to="{ path: '/chamyto1' }">Chamyto 1+1</router-link>
          </article>
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/chamyto-1-1.png">
          </figure>
          <article class="notification is-primary">
            <p class="title">Chamyto 1+1</p>
            <p class="subtitle">5 bolsocoins</p>
            <router-link :to="{ path: '/chamyto1' }">Chamyto 1+1</router-link>
          </article>
        </div>
        <div class="column">
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/iogurte-100g.png">
          </figure>
          <article class="notification is-info">
            <p class="title">Iogurte 100g</p>
            <p class="subtitle">10 bolsocions</p>
            <router-link :to="{ path: '/chamyto1' }">Chamyto 1+1</router-link>
          </article>
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/iogurte-100g.png">
          </figure>
          <article class="notification is-info">
            <p class="title">Iogurte 100g</p>
            <p class="subtitle">10 bolsocions</p>
            <router-link :to="{ path: '/chamyto1' }">Chamyto 1+1</router-link>
          </article>
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/iogurte-100g.png">
          </figure>
          <article class="notification is-info">
            <p class="title">Iogurte 100g</p>
            <p class="subtitle">10 bolsocions</p>
            <router-link :to="{ path: '/chamyto1' }">Chamyto 1+1</router-link>
          </article>
        </div>
        <div class="column">
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/leite-fermentado-450.png">
          </figure>
          <article class="notification is-info">
            <p class="title">Leite fermentado 450g</p>
            <p class="subtitle">12 bolsocoins</p>
            <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
          </article>
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/leite-fermentado-450.png">
          </figure>
          <article class="notification is-info">
            <p class="title">Leite fermentado 450g</p>
            <p class="subtitle">12 bolsocoins</p>
            <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
          </article>
          <figure class="image is-300x300">
    <img src="https://www.nestle.com.br/sites/g/files/pydnoa436/files/2021-10/leite-fermentado-450.png">
          </figure>
          <article class="notification is-info">
            <p class="title">Leite fermentado 450g</p>
            <p class="subtitle">12 bolsocoins</p>
            <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
          </article>
        </div>
      </div>
    </div>
  </div>
</template>