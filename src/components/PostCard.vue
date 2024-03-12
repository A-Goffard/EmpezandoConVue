<template>
    <div class="post-card">
        <h3>Título</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam cumque, tempora, repellat fuga autem accusamus assumenda voluptatibus voluptatem quo sed consequatur fugiat et excepturi velit explicabo atque placeat neque quidem!</p>
        <!-- ¿cómo usamos un componente aquí? Importo en el script el componente desde su posición en las carpetas-->
    <PostButton /><!-- después de importar solo hay que poner la etiqueta donde quieres que aparezca -->
    
    </div>
    
</template>
  
  <script setup>
    import PostButton from "./PostButton.vue"
  </script>
  
  <style scoped>
.post-card{
    border-radius: 1rem;
    padding: 0.8rem;
    margin: 0.3rem;
    border: solid blue 0.3rem;
}
  </style>
  