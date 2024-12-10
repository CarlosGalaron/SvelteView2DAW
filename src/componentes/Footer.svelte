<script>
    import FooterIcon from "./FooterIcon.svelte";
    import carta from ".././assets/./images/carta.png";
    import facebook from ".././assets/./images/facebook.png";
    import x from ".././assets/./images/x.png";
    import instagram from ".././assets/./images/instagram.png";
    import whatsapp from ".././assets/./images/whatsapp.png";

</script>

<div class="footer-container">
    <div class="footer-icon-strecher">
        <FooterIcon src={facebook} alt="facebook" imgClass="footer-fb-pic" />
        <FooterIcon src={instagram} alt="instagram" imgClass="footer-insta-pic" />
        <FooterIcon src={x} alt="twitter" imgClass="footer-x-pic" />
        <FooterIcon src={whatsapp} alt="whatsapp" imgClass="footer-whatsapp-pic" />
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

</style>
