<template>
  <div>
    
    <!-- carousel com imagens -->
    <b-carousel>
      <b-carousel-item>
        <b-image class="image is-128x128" src="https://mir-s3-cdn-cf.behance.net/projects/404/b11cea51769163.Y3JvcCw2NzAsNTI0LDI5LDExMQ.png"></b-image>
      </b-carousel-item>
      <b-carousel-item>
        <b-image class="image is-128x128" src="https://mir-s3-cdn-cf.behance.net/projects/404/7f25d271954537.Y3JvcCwyODc2LDIyNTAsNTYsMA.png"></b-image>
      </b-carousel-item>      
      <b-carousel-item>
        <b-image class="image is-128x128" src="https://d1l3jc4magixw.cloudfront.net/cases/2018/BR_2018_12/2018_BR_2018_12_hero_1.jpg"></b-image>
      </b-carousel-item>            
    </b-carousel>

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

    <div class="columns mt-4">
      <div class="column">
        <article class="notification is-danger has-text-centered">
          <p class="title">Site oficial de venda de produtos da chamyto (O genio da chamyto daria uma surra no genio do habbibs)</p>
        </article>
      </div>
    </div>    
  </div>
</template>
