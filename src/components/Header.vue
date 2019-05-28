<template>
    <div id="header-wrapper">
        <img id="logo" src='../assets/logo.png' height=75px width=75px/>
        <h1>Longer Blog Title</h1>
    </div>
</template>

<script>
export default {
    name: 'Header', 
}
</script>
<style>
    #logo {
      margin: auto 5vw;    
    }
    h1 { 
        font-size: 56px;
        margin-left: 10vw; 
        padding-left: 4vw;  
    }
    
    #header-wrapper {
        display: flex;
        justify-content: flex-start; 
        padding: .5em; 
        margin: .5em; 
        margin-bottom: 1em; 
    }
</style>


