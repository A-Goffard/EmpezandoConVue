<template>
    <!-- código html -->
    <div>
        <h1 v-bind:style="miColor">Hola {{miNombre}}, ¿qué tal estás hoy? Parece que tienes {{ edad - 10}} años</h1>
        <!-- v-bind:style es lo mismo que :style -->
        <button v-on:click="">Aceptar</button>
        <!-- v-on:click es lo mismo que @click -->
    </div>
</template>


<script setup>//setup es para que la exportación se haga automáticamente
//codigo js
const miNombre = "Aintzane";
const edad = 25;
const miColor = "color:rgb(184, 93, 196);font-size:3rem"
</script>

<style scoped>/* scoped es para que los estilos solo afecten a esta página */
/* código CSS */

</style>