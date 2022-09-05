<template>
  <div class="container is-fluid">

    <b-navbar>
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Home
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/produtos' }">
                Lista de produtos
            </b-navbar-item>          
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a href="/cadastro" class="button is-info">
                        <strong>Cadastre-se</strong>
                    </a>
                    <a href="/login" class="button is-light">
                        Login
                    </a>
                    <a href="/carrinho" class="button is-light">
                        Carrinho
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>

    <Nuxt/>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Nuxt exemplo</strong> by José Elias. 
          <a target="_blank" href="https://eprevs.com">FAE Centro Universitário</a>
        </p>
      </div>
    </footer>      
    
  </div>
</template>

