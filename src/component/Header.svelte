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
        <navbar >
            <ul>
                <li><a class='about' href="#about">About</a></li>
                <li><a class='services' href="#services">Services</a></li>
                <li><a class='projects' href="#projects">Projects</a></li>
                <li><a class='contact' href="#contact">CONTACT</a></li>    
            </ul>
        </navbar>
    </div>         
</header>

<style>
    .srcHeader {
        width: 1440px;
        height: 800px;
        left: 0px;
        top: 0px;
        position: absolute;
    }  
    h1 {
        position: relative;
        width: 750px;
        height: 69px;
        left: 344.5px;
        top: 195px; 
        font-family: 'Fraunces', serif;
        /* font-family: Fraunces 9pt Soft; */
        font-style: normal;
        font-weight: 900;
        font-size: 56px;
        line-height: 69px;
        color: #FFFFFF;
        letter-spacing: 8.75px;
    }
    .arrow {
        position: relative;
        width: 30px;
        height: 107.48px;
        left: 705px;
        top: 220px;   
    }
    .header-top {
        position: relative;
        width: 1352px;
        height: 56px;
        left: 40px;
        top: -220px;   
    }
    .logo {
        position: absolute;
        display: flex;
        justify-content: flex-start;
        width: 170px;
        height: 33px;
        left: 0px;
        top: 12px;
    }
    /* nav */
    navbar {
        display: flex;
        justify-content: flex-end;

        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 25px;
        letter-spacing: -0.128571px;
        color: #FFFFFF;
        height: 25px;
        top: calc(50% - 25px/2 + 0.5px);

        left: 89.64%;
        right: 0%;
        top: 0%;
        bottom: 0%;
    }
    navbar > ul {
        list-style-type: none;
        display: flex;
        justify-content: space-around;
        width: 40vw;
    }
    navbar > ul > li > a{
        text-decoration: none;
        color: white;
        padding-right: 20px;
    }   
    .contact {
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: bold;
        font-size: 15px;
        letter-spacing: -0.107143px;
        color: white;
    }
    /* nav */
</style>