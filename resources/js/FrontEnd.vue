<template>



  <div>
    <NavbarComponent></NavbarComponent>

    <div class="container">

      <router-view></router-view>
      
    </div>
    
    
  </div>


</template>

<script>
import NavbarComponent from './components/navbar.component.vue';
import PostList from './components/PostList.vue';
export default {
  components: { NavbarComponent, PostList },
  data() {
    return {

      message: "ciao",

    };
  }
}
</script>