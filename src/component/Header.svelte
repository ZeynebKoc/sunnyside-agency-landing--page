<script>  
    let srcHeader = './img/image-header.jpg'; 
    let srcArrow = './img/icon-arrow-down.svg';
    let srcLogo = './img/logo.svg';
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
                <button class='contact'>CONTACT </button>
            </ul>
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
        position: relative;
        height: 69px;
        width: 750px;
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
        position: relative;
        left: 705px;
        top: 290px;   
    }
    .header-top {
        position: relative;
        left: 40px; 
        top: -153px;  
    }
    .logo {
        position: absolute;
        left: 0px;
        top: 12px;
        height: 33px;
        width: 170px;

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
        left: 885px;
    } 
    .services {
        position: absolute;
        left: 980px;
    }
    .projects {
        position: absolute;
        left: 1099px;
    }
    .contact {
        position: absolute;
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: bold;
        font-size: 15px;
        letter-spacing: -0.107143px;
        color: rgba(36, 48, 62, 1);
        background-color: rgba(255, 255, 255, 1);
        border-radius: 28px;
        height: 56px;
        width: 140px;
        left: 1185px;
        top: 0px;
        border: none;
    }
    .contact:hover {
        color: rgba(255, 255, 255, 1);
        background-color: rgba(255, 255, 255, 0.25);
        border: none;
        cursor: pointer;
    }
    /* nav */
</style>