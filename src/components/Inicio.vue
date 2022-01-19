<template>
  <div class="Inicio">
    <h1>Push notifications com One Signal</h1>
    <p>
      Aplicação desenvolvida com a finalidade de aprimorar estudo de push notifications com a API One Signal
    </p>
    <h3>Repositório do projeto</h3>
    <ul>
      <li><a href="https://github.com/ArikBartzadok/vue-notificacoes-onesignal" target="_blank" rel="noopener">@ArikBartzadok/vue-notificacoes-onesignal</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Inicio',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: var(--electric-blue);
}
</style>
