<script>
    import Header from "./Header.svelte";
    import Footer from "./Footer.svelte";
</script>

<main class="homepage-container">
    <Header />
    <div class="homepage-body">
        <div class="login-container">
            <h1 class="login-title">Bienvenido de nuevo!</h1>
            <input
                type="text"
                class="input-text"
                placeholder="Nombre de usuario"
            />
            <input
                type="password"
                class="input-text"
                placeholder="Contraseña"
            />
            <button class="button-login">Iniciar sesión</button>
            <p class="register-link">¿No estás registrado?</p>
        </div>
    </div>
    <Footer />
</main>

<style>
    .homepage-container{
        width: 100vw;
        height: 100vh;
        background-color:blanchedalmond;
        color: black;
        justify-content: flex-start;
        align-items: stretch;
        display: flex;
        flex-direction:column;
        overflow-y: hidden;
            
    }

    .homepage-body{
        width: 100vw;
        height: 75vh;
        justify-content: center;
        align-items: center;
        display: flex;
        flex: 1;
    }

    .login-container{
        padding-top: 2%;
        width: 30vw;
        height: 45vh;
        justify-content: space-between;
        align-items: center;
        display: flex;
        flex-direction: column;
        background-color: rgb(55, 94, 201);
        color: white;
        border: 2px solid darkblue;
        border-radius: 12px;        
        box-sizing: border-box;
    }

    .login-title{
        text-align: center;
        font-size: 36px;
        font-family: Arial, Helvetica, sans-serif;
        color: white;
        margin: 1%;
        font-weight: bolder;
        cursor: default;
    }
    .input-text{
        width: 20em;
        height: 32px;
        border-radius: 10px;
        border: none;
        margin: 1%;
        border: 1px solid black;
        box-sizing: border-box;
        padding-left: 5px;
                
    }

    .button-login{
        width: 10em;
        height: 3em;
        font-size: 16px;
        border-radius: 8px;
        border: none;
        margin: 1%;
        background-color: darkgreen;
        border: 2px solid darkgray;
        color: white;
        box-sizing: border-box;
    }

    .button-login:hover{
        background-color: darkcyan;
        color: white;
        border: 2px solid black;
        cursor: pointer;
        box-sizing: border-box;
    }

    .register-link{
        cursor: pointer;
        color: darkgray;
        font-style: oblique;
    }

    .register-link:hover{
        color: white;
        text-shadow: 2px;
    }

</style>
