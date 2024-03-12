<template>
    <div class="post-container">
        <PostCard />
        <PostCard />
        <PostCard />
        <PostCard />

    </div>
    
</template>
  
  <script setup>
    import PostCard from "./PostCard.vue"
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
.post-container{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
}
  </style>
  