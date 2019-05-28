<template>
   <div id="nav-bar">
       <nav>
           <a href='#' class="nav-link"> Home</a>
           <a href='#' class="nav-link" >Contact</a>
           <a href='#' class="nav-link" >Sign In</a>
           <a href='#' class="nav-link" >Sign Up</a>
       </nav>
    </div> 
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style>
#nav-bar {
    padding-top: 0;
    margin-top: 0; 
}
.nav-link {
    display: inline; 
    padding:0 1em; 
}
</style>
