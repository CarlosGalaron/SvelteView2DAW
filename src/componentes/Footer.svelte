<script>
    import carta from ".././assets/./images/carta.png";
    import facebook from ".././assets/./images/facebook.png";
    import x from ".././assets/./images/x.png";
    import instagram from ".././assets/./images/instagram.png";
    import whatsapp from ".././assets/./images/whatsapp.png";

</script>

<div class="footer-container">
    <div class="footer-icon-strecher">
    <div class="footer-icon-container"><img class="footer-fb-pic" src={facebook} alt="facebook" /></div>
    <div class="footer-icon-container"><img class="footer-insta-pic" src={instagram} alt="instagram" /></div>
    <div class="footer-icon-container"><img class="footer-x-pic" src={x} alt="twitter" /></div>
    <div class="footer-icon-container"><img class="footer-whatsapp-pic" src={whatsapp} alt="whatsapp" /></div>
</div>
    <div class="footer-contact-container">
        <div class="footer-text-container">
            <p class="footer-text-contact">Contacta con nosotros</p>
            <p class="footer-text-email">correo@correo.com</p>            
        </div>
        <img class="footer-contact-pic" src={carta} alt="carta" />
    </div>
</div>

<style>
    .footer-container {
        width: 100vw;
        height: 15vh;
        background-color: rgb(55, 94, 201);
        border: 2px solid darkblue;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        padding: 0 1rem;
        box-sizing: border-box;
        
    }

    .footer-icon-strecher {
        width: 100vW;
        height: 10vh;
        display: flex;
        flex-direction: row;
        justify-content: left;
        align-items: center;
        row-gap: 1rem;
    }

    .footer-icon-container {
        width: 2.5em;
        height: 2.5em;
        background-color: rgb(55, 94, 201);
        color: rgb(55, 94, 201);        
        border: 2px solid rgb(7, 7, 63);
        box-sizing: border-box;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 4% 0 4%;
        border-radius: 10%;
    }



    .footer-contact-container{
        display: flex;
        margin-right: 20px;        
        flex-direction: row;
        font-size: 16px;
        justify-content: center;
        align-items: center;
        padding: 1rem;
    }

    .footer-text-email{
        color: orange;
    }

    .footer-contact-pic {
        height: 8vh;
    }

    .footer-fb-pic, .footer-insta-pic, .footer-x-pic, .footer-whatsapp-pic{
        height: 10vh;
        margin: 0.5 0.5rem;
    }
</style>
