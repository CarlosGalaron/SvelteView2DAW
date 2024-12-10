<script>
    export let children;
</script>

<button class="header-button">{children}</button>

<style>
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