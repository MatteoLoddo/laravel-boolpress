<template>
  <div>
    <h1>Pagina Home</h1>
    <h2>Lista Post</h2>
      <PostList></PostList>
  </div>
</template>

<script>
import PostList from '../components/PostList.vue';
  export default{
    components: { PostList }
}
</script>