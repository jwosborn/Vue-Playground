<template>
       <nav id="nav-bar">
           <a href="#" v-for="link in links" :key="link" class="nav-link">{{ link }}</a>
       </nav>
</template>

<script>
export default {
    name: 'Nav',
    data () {
        return {
            links: ["Home", "Contact", "Sign in", "Sign Up"],
            isSelected: false
        }
    }
}
</script>

<style>

#nav-bar {
    scroll-behavior: smooth;
    margin-right: -60vw; 
}
.nav-link {
    font-size: 1.5em; 
    display: inline; 
    padding:0 1em; 
    color: #18a689;
}
</style>
