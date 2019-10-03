<template>
  <div class="navbar">
    <div class="nav">
     <router-link>
      <span class="nav-title">Smoithies Magic Smoothies </span>
     </router-link>
     <a href="" class="btn-floating btn-large halfway-fab pink">
       <router-link>
        <i class="material-icons">add</i>       
       </router-link>
     </a>
    </div>
  </div>
</template>

<script>
 export default{
   name: "NavBar",
   data() {
     return
   }
 }
</script>

<style>
.navbar nav {
  padding: 0 20px;
  
}
</style>