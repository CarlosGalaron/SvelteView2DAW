<script>
    export let src;
    export let alt;
    export let imgClass;
</script>

<div class="footer-icon-container">
    <img class={imgClass} src={src} alt={alt} />
</div>

<style>
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

    .footer-fb-pic, .footer-insta-pic, .footer-x-pic, .footer-whatsapp-pic{
        height: 10vh;
        margin: 0.5 0.5rem;
    }
</style>