<style>
    #backdrop
    {
        background-color: black;
    }
    


</style>

<script lang="ts">
    let {children} = $props();
</script>

<body id = "backdrop">
    <h>is this thing on?</h>
    {@render children()}
    <footer> Welcome to the program init </footer>
</body>

