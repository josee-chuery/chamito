<template>
  <div>
    <br>
    <div class="columns is-centered">
      <div class="column is-4">
        <p class="title has-text-centered" ><strong>Cadastro</strong></p>
        <form class="box">
          <div class="field">
            <label class="label">Nome Completo</label>
            <div class="control">
              <input class="input" type="text" placeholder="João da Silva">
            </div>
          </div>
          <div class="field">
            <label class="label">CPF</label>
            <div class="control">
              <input class="input" type="text" placeholder="XXX.XXX.XXX-XX">
            </div>
          </div>
          <div class="field">
            <label class="label">Data de Nascimento</label>
            <div class="control">
              <input class="input" type="text" placeholder="XX/XX/XXXX">
            </div>
          </div>
          <div class="field">
            <label class="label">Telefone</label>
            <div class="control">
              <input class="input" type="tel" placeholder="(DDD)XXXXX-XXXX">
            </div>
          </div>
          <div class="field">
            <label class="label">Email</label>
            <div class="control">
              <input class="input" type="email" placeholder="joao@exemplo.com">
            </div>
          </div>
          <div class="field">
            <label class="label">Confirmar Email</label>
            <div class="control">
              <input class="input" type="email" placeholder="joao@exemplo.com">
            </div>
          </div>
          <div class="field">
            <label class="label">Senha</label>
            <div class="control">
              <input class="input" type="password" placeholder="********">
            </div>
          </div>
          <div class="field">
            <label class="label">Confirmar Senha</label>
            <div class="control">
              <input class="input" type="password" placeholder="********">
            </div>
          </div>
          <button class="button is-info">Entrar</button>
        </form>
        <br>
      </div>
    </div>
  </div>
</template>