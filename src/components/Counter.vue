<template>
    <h3>{{ counter }}</h3>
    <button @click="addCounter">Incrementar</button>
</template>

<script>
/* El ref se pone para que actualice el valor del counter cada vez que se ejecuta. Hay que ponerlo en el import y en la funcion. Y en vez de usar counter++, usar counter.value++ */
    
/* esto es la definición de un componente */
import { defineComponent, ref } from "vue";
export default defineComponent({
    name: "Counter",
    setup(){
        let counter = ref(0);
        const addCounter = () => {
            counter.value++
            console.log(counter);
        }
        return {counter, addCounter}
    }

})

/* si ponemos en la etiqueta del script setup, no es necesario nombrar tantas cosas como arriba, quedaría como abajo */
/* import { ref } from "vue";

        let counter = ref(0);
        const addCounter = () => {
            counter.value++
            console.log(counter);
        }


}) */
</script>