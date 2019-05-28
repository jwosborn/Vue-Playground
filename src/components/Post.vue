<template>
    <div id="post-wrapper">
        <p>
            {{ content }}
        </p>
    </div>
</template>

<script>

export default {
    data () {
    return {    
        content: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
    }
},
    name: 'Post'
}
</script>

<style>
    #post-wrapper {
        padding: 1em 0;
        margin: 0  10vw; 
    }
    p {
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
</style>
