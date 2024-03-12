<template>
    <div>
        <button class="post-btn">Acceder</button>
    </div>
    
</template>
  
<script setup>//setup es para que la exportacion del componente funcione bien

</script>
  
<style scoped> /* es para que solo afecte a este componente*/
.post-btn {
    padding: 0.8rem 1rem;
    background-color: aquamarine;
    color: black;
    border-radius: 1rem;
    border: 0;
    outline: 0;
    transition: 200ms ease;
    margin: 0.5rem;
}
.post-btn:hover {
    padding: 1rem;
    background-color: rgb(83, 221, 175);
    color: rgb(31, 19, 139);
    border: 0;
    outline: 0;
}

</style>
  