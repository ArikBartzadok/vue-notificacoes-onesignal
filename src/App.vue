<template>
  <img class="logo" alt="Logo do projeto" src="./assets/ovni-perspectiva-sombra.png">
  <Inicio/>
</template>

<script>
import Inicio from './components/Inicio.vue'

export default {
  name: 'App',
  components: {
    Inicio
  }
}
</script>

<style>
:root {
  --black: #000000ff;
  --violet-blue-crayola: #646FD3ff;
  --electric-blue: #90FFFFff;
  --violet-blue-crayola-2: #646FD3ff;
  --violet-blue-crayola-3: #646FD3ff;
}

body {
  font-family: 'Roboto', sans-serif;
  background-color: var(--violet-blue-crayola);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
}

.logo {
  max-width: 200px;
}
</style>
