<script>

</script>

<div class="header-container">
    <div class="header-icon_container"></div>
    <button class="header-button">BIBLIOTECA</button>
    <button class="header-button">INTERCAMBIO</button>
    <button class="header-button">TIENDA</button>
    <button class="header-button">PUBLICACIONES</button>
    <button class="header-button">AUDIOLIBROS</button>
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

    .header-button{
        width: 12%;
        height: 3em;
        color: black;
        background-color: white(55, 94, 201);
        border: 2px solid rgb(7, 7, 63);
        box-sizing: border-box;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 4% 0 4%;
        border-radius: 16%;
        font-size: 16px;
        font-weight: 1000;
        cursor: pointer;
    }

    .header-button:hover{
        background-color: lightcyan;
        color: black;
    }

</style>