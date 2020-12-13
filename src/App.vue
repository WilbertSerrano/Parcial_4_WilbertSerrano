<template>
  <div id="app">
    <Menu />
    <Header />
    <Contenido />
    <PieDePagina />

  </div>
</template>

<script>
import Menu from './components/Menu'
import Header from './components/Header'
import Contenido from './components/Contenido'
import PieDePagina from './components/PieDePagina'

export default {
  name: 'App',
  components: {
    Menu,
    Header,
    Contenido,
    PieDePagina
  }
}
</script>
