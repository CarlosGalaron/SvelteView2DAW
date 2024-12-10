<script>
    import HeaderButton from "./HeaderButton.svelte";    
</script>

<div class="header-container">
    <div class="header-icon_container"></div>
    <HeaderButton children = "Biblioteca"></HeaderButton>
    <HeaderButton children = "Intercambio"></HeaderButton>
    <HeaderButton children = "Tienda"></HeaderButton>
    <HeaderButton children = "Publicaciones"></HeaderButton>
    <HeaderButton children = "Audiolibros"></HeaderButton>
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