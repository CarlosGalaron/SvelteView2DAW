<script>
    import Button from "./Button.svelte";    
</script>

<div class="header-container">
    <div class="header-icon_container"></div>
    <Button children = "Biblioteca"></Button>
    <Button children = "Intercambio"></Button>
    <Button children = "Tienda"></Button>
    <Button children = "Publicaciones"></Button>
    <Button children = "Audiolibros"></Button>
</div>

<style>
    .header-container{
        width: 100vw;
        height: 10vh;
        background-color: rgb(55, 94, 201);
        border: 2px solid darkblue;
        box-sizing: border-box;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;

    }
</style>