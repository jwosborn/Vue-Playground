<template>
       <nav id="nav-bar">
           <a href='#' class="nav-link"> Home</a>
           <a href='#' class="nav-link" >Contact</a>
           <a href='#' class="nav-link" >Sign In</a>
           <a href='#' class="nav-link" >Sign Up</a>
       </nav>
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style>

#nav-bar {
    scroll-behavior: smooth;
    padding-bottom: 1.5em;
    margin-right: -60vw;  
}
.nav-link {
    font-size: 1.5em; 
    display: inline; 
    padding:0 1em; 
}
</style>
