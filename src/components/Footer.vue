<template>
    <div id="footer-wrapper">
        <span id="copyright">
            &copy; Jeremy Osborn 2019
        </span>
        <span>
            <a href="#" class="footer-link">About</a>
            <a href="#" class="footer-link">Policies</a>
            <a href="#" class="footer-link">Contact</a>
        </span>
    </div>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style>
    #footer-wrapper {
        display: flex; 
        justify-content: space-between; 
        background-color: #2C3E50;
        padding: 1em 0; 
    }
    .footer-link {
        font-size: 1em; 
        color:  #18a689;
        margin: 0 1em; 
        flex-grow: 2; 
    }
    #copyright {
        color: white; 
    }
</style>
