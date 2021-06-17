<script>  
    let srcHeader = '././img/image-header.jpg'; 
    let srcArrow = '././img/icon-arrow-down.svg';
    let srcLogo = '././img/logo.svg';
</script>

<header>
    <img src={srcHeader} class='srcHeader' alt='HeaderPhoto'>
    <h1>WE ARE CREATIVES</h1>
    <img src={srcArrow} class='arrow' alt='ArrowPhoto'>
    <div class='header-top'>
        <img src={srcLogo} class='logo' alt='SunnysideLogo'>
        <navbar>
            <ul>
                <li><a class='about' href="#about">About</a></li>
                <li><a class='services' href="#services">Services</a></li>
                <li><a class='projects' href="#projects">Projects</a></li>
                <li><a class='contact' href="#contact">CONTACT</a></li>    
            </ul>
            <span class='bg-contact'></span>
        </navbar>
    </div>         
</header>

<style>
    header {
        position: relative;
        width: 1440px;
        height: 800px;
        left: 0px;
        top: 0px;
    }
    .srcHeader {
        width: 1440px;
        height: 800px;
        left: 0px;
        top: 0px;
        z-index:-1;
        position: absolute;
    }  
    h1 {
        position: absolute;
        width: 750px;
        height: 69px;
        left: 344.5px;
        top: 195px; 
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 56px;
        line-height: 69px;
        color: #FFFFFF;
        letter-spacing: 8.75px;
    }
    .arrow {
        position: absolute;
        width: 30px;
        height: 107.48px;
        left: 705px;
        top: 360.54px;   
    }
    .header-top {
        position: relative;
        width: 1352px;
        height: 56px;
        left: 40px; 
        top: 34px;  
    }
    .logo {
        position: absolute;
        width: 170px;
        height: 33px;
        left: 0px;
        top: 12px;
    }
    /* nav */
    navbar {
        position: absolute;
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 25px;
        letter-spacing: -0.128571px;
        color: #FFFFFF;
        top: 0px;
    }
    navbar > ul > li > a{
        color: white;
    }  
    .about {
        position: absolute;
        height: 25px;
        width: 48px;
        left: 885px;
    } 
    .services {
        position: absolute;
        height: 25px;
        width: 72px;
        left: 980px;
    }
    .projects {
        position: absolute;
        height: 25px;
        width: 66px;
        left: 1099px;
    }
    .contact {
        position: absolute;
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: bold;
        font-size: 15px;
        letter-spacing: -0.107143px;
        color: white;
        
        height: 28px;
        width: 78px;
        left: 1218px;
        top: 16px;
    }
    .bg-contact {
        position: absolute;
        background-color: rgba(255, 255, 255, 0.453);
        border-radius: 28px;
        height: 56px;
        width: 140px;
        left: 1185px;
        top: 0px;
    }
    /* nav */
</style>