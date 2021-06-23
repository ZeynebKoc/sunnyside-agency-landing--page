<script>  
    let srcMilk = '././img/image-gallery-milkbottles.jpg'; 
    let srcOrange = '././img/image-gallery-orange.jpg';
    let srcCone = '././img/image-gallery-cone.jpg';
    let srcSugar = '././img/image-gallery-sugarcubes.jpg'; 

    let srcLogo = '././img/sunnyside.svg'; 

    let srcFacebook = '././img/icon-facebook.svg';
    let srcInstagram = '././img/icon-instagram.svg';
    let srcTwitter = '././img/icon-twitter.svg';
    let srcPinterest = '././img/icon-pinterest.svg'; 
</script>

<footer>
    <div class='footer-img'>
        <img src={srcMilk} class='srcMilk' alt='MilkPhoto'>
        <img src={srcOrange} class='srcOrange' alt='OrangePhoto'>
        <img src={srcCone} class='srcCone' alt='ConePhoto'>
        <img src={srcSugar} class='srcSugar' alt='SugarPhoto'>
    </div>
    <div class='footer-bottom'>
        <div class='footer-content'>
            <img src={srcLogo} class='logo' alt='SunnysideLogo'>
            <ul class='nav-list'>
                <li><a class='about' href="#about">About</a></li>
                <li><a class='services' href="#services">Services</a></li>
                <li><a class='projects' href="#projects">Projects</a></li>    
            </ul>
            <div class='icons'>
                <img src={srcFacebook} class='srcFacebook' href="#" alt='FacebookIcon'>
                <img src={srcInstagram} class='srcInstagram'href="#"  alt='InstagramIcon'>
                <img src={srcTwitter} class='srcTwitter' href="#" alt='TwitterIcon'>
                <img src={srcPinterest} class='srcPinterest'href="#"  alt='PinterestIcon'>
            </div>
        </div>
    </div>
</footer>

<style>
	footer {
        position: absolute;
        width: 1440px;
        height: 797px;
        top: 3377px;
    }
    .footer-img {
        position: relative;
        display:flex;
        flex-direction: row;
        width: 360px;
        height: 447px;
        top: 0px;
    }
    .footer-bottom {
        display:flex;
        flex-direction: column;
        align-items: center;
        height: 350px;
        background: #90D4C6;
    }
    .footer-content {
        position: relative;
        display:flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        width: 300px;
        height: 206px; 
        padding: 70px;
    } 
    .logo {
        display:flex;
        flex-direction: column;
        flex-wrap: wrap;
        align-items: center;
        width: 170px;
        height: 33px;
        left: 628px;
        top: 3896px;
    }
    .nav-list {
        position: relative;
        display: flex;
        flex-direction: row;
        left: 0px;
        top: -20px;
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 25px;
        letter-spacing: -0.128571px;
    }
    a {
        color: #458D7E;
        padding-right: 70px;
    }
    a:hover {
        color: #FFFFFF;
    }
    .icons {
        position: relative;
        height: 20px;
        width: 164px;
        left: -670px;
        top: -4075px;  
    }
    .srcFacebook {
        position: relative;
        width: 20px;
        height: 20px;
        left: 670px;
        top: 4082px;
    }
    .srcFacebook:hover {
        cursor: pointer;
        filter: invert(42%) sepia(93%) saturate(1%) hue-rotate(130deg) brightness(500%) contrast(119%);
    }
    .srcInstagram {
        position: relative;
        width: 20px;
        height: 20px;
        left: 697px;
        top: 4082px;
    }
    .srcInstagram:hover {
        cursor: pointer;
        filter: invert(42%) sepia(93%) saturate(1%) hue-rotate(130deg) brightness(500%) contrast(119%);
    }
    .srcTwitter {
        position: relative;
        width: 20px;
        height: 16.25px;
        left: 721px;
        top: 4084.25px;
    }
    .srcTwitter:hover {
        cursor: pointer;
        filter: invert(42%) sepia(93%) saturate(1%) hue-rotate(130deg) brightness(500%) contrast(119%);
    }
    .srcPinterest {
        position: relative;
        width: 20px;
        height: 20px;
        left: 746px;
        top: 4082px;
    }
    .srcPinterest:hover {
        cursor: pointer;
        filter: invert(42%) sepia(93%) saturate(1%) hue-rotate(130deg) brightness(500%) contrast(119%);
    }
</style>