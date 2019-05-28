<template>
    <div id="header-wrapper">
        <img id="logo" src='../assets/logo.png' height=75px width=75px/>
        <h1>Blog Title</h1>
    </div>
</template>

<script>
export default {
    name: 'Header', 
}
</script>
<style>
    #logo {
      margin: auto 0;    
    }
    h1 { 
        padding: 0 30vw; 
        font-size: 56px; 
    }
    
    #header-wrapper {
        display: flex;
        padding: 1em; 
        margin: 1em; 
    }
</style>


