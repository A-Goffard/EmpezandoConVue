<template>
  <div>
    <div>
      <Equipo msg="Trifuerza"/>
    </div>
    <Counter />
    <Counter />
    <ExampleSelectiveVue />
    <PostContainer /><!-- este contenedor importado contiene los componentes dentro del propio componente -->
  </div>
</template>

<script setup>
import Equipo from './components/Equipo.vue'/* esto es para importar el componenete Equipo.vue */
import PostContainer from "./components/PostContainer.vue"
import Counter from "./components/Counter.vue"
import ExampleSelective from "./components/ExampleSelective.vue"
import ExampleSelectiveVue from './components/ExampleSelective.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #000000;
  margin-top: 3rem;

}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  background-color: rgb(240, 255, 255);
}

.trifuerza_logo {
width: 2rem;
}

.cabecera {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 1rem;
}
</style>
