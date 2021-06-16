<script>  
    let srcMilk = '././img/image-gallery-milkbottles.jpg'; 
    let srcOrange = '././img/image-gallery-orange.jpg';
    let srcCone = '././img/image-gallery-cone.jpg';
    let srcSugar = '././img/image-gallery-sugarcubes.jpg'; 

    let srcLogo = '././img/logo.svg'; 

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
                <img src={srcFacebook} class='srcFacebook' alt='FacebookIcon'>
                <img src={srcInstagram} class='srcInstagram' alt='InstagramIcon'>
                <img src={srcTwitter} class='srcTwitter' alt='TwitterIcon'>
                <img src={srcPinterest} class='srcPinterest' alt='PinterestIcon'>
            </div>
        </div>
    </div>
</footer>

<style>
	footer {
        position: relative;
        width: 1440px;
        height: 797px;
        top: 3377px;
    }
    .footer-img {
        display:flex;
        flex-direction: row;
        width: 360px;
        height: 447px;
        top: 3377px;
    }
    .footer-bottom {
        display:flex;
        flex-direction: column;
        align-items: center;
        height: 350px;
        background: #90D4C6;
    }
    .footer-content {
        display:flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        width: 300px;
        height: 206px; 
        padding: 70px;
    } 
    .logo {
        color: #458D7E;
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
        display: flex;
        flex-direction: row;
        width: 300px;
        height: 25px;
        left: 570px;
        top: 3969px;

        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 25px;
        letter-spacing: -0.128571px;
    }
    ul {
        list-style-type: none;
        display: flex;
        float:left;
    }
    a {
        text-decoration: none;
        color: #458D7E;
        padding-right: 50px;
    }
    .icons {
        float:left;
        display:flex;
        flex-wrap: row wrap;
        align-content: space-between; 
    }
    .srcFacebook {
        width: 20px;
        height: 20px;
        left: 636px;
        top: 4082px;
    }
    .srcInstagram {
        width: 20px;
        height: 20px;
        left: 684px;
        top: 4082px;
    }
    .srcTwitter {
        width: 20px;
        height: 16.25px;
        left: 732px;
        top: 4084.25px;
    }
    .srcPinterest {
        width: 20px;
        height: 20px;
        left: 780px;
        top: 4082px;
    }

    
</style>