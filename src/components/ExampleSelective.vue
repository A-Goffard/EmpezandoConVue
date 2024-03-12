<template>
    <div>
        <div><!-- en este caso los componentes no se pintan dentro del DOM, solo el que corresponde. Mejor usar esto cuando los cambios que se van a generar en el renderizado es poco -->
            <h1 v-if="age < 18">Eres menor de edad</h1>
            <h1 v-else>Eres mayor de edad</h1>
        </div>
        <div><!-- en este caso los dos se pintan en el DOM, pero cambia el display none para que se vean o no. En aplicaciones con muchos cambios de renderizado son muchos mejor usar esto -->
            <h1 v-show="age2 < 18">Eres menor de edad</h1>
            <h1 v-show="age2 >= 18">Eres mayor de edad</h1>
        </div>
    </div>

</template>

<script setup>

let age = 10;
let age2 = 25;

</script>

<style scoped>

</style>