<script> 
    let srcPhoto1 = '././img/image-emily.jpg';
    let srcPhoto2 = '././img/image-thomas.jpg';
    let srcPhoto3 = '././img/image-jennie.jpg';
</script>

<div class='testimonial'>
    <h3>CLIENT TESTIMONIALS</h3>
    <div class='people'>
        <div class='person1'>
            <img src={srcPhoto1} class='srcPhoto1' alt='srcPhoto1'>
            <p class='text'>We put our trust in Sunnyside and they<br />
                delivered, making sure our needs were met<br />
                and deadlines were always hit.</p>
            <h2>Emily R.</h2>
            <p class='profession'>Marketing Director</p>
        </div>
        <div class='person2'>
            <img src={srcPhoto2} class='srcPhoto2' alt='srcPhoto1'>
            <p class='text'>Sunnyside’s enthusiasm coupled with their<br />
                keen interest in our brand’s success made it<br />
                a satisfying and enjoyable experience.</p>
            <h2>Thomas S.</h2>
            <p class='profession'>Chief Operating Officer</p>
        </div>
        <div class='person3'>
            <img src={srcPhoto3} class='srcPhoto3' alt='srcPhoto1'>
            <p class='text'>Incredible end result! Our sales increased<br /> 
                over 400% when we worked with Sunnyside.<br />
                Highly recommended!</p>
            <h2>Jennie F.</h2>
            <p class='profession'>Business Owner</p>
        </div>
    </div>
</div>

<style>
    .testimonial {
        position: relative;
        height: 457px;
        width: 1110px;
        left: 165px;
        top: 0px;
    }
    .people{
        position: relative;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-around;
        width: 1110px;
        height: 457px;
        left: 0px;
        top: -140px;
    }
    .person1 {
        position: relative;
        height: 96px;
        width: 350px;
        left: 0px;
        top: 236px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .person2 {
        position: relative;
        height: 96px;
        width: 350px;
        left: 0px;
        top: 236px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .person3 {
        position: relative;
        height: 96px;
        width: 350px;
        right: 0px;
        top: 236px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    h3 {
        position: relative;
        left: 0px;
        top: 190px;
        text-align: center;
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 20px;
        line-height: 25px;
        text-align: center;
        letter-spacing: 5px;
        color: #A7AAAD;
    }
    img {
        display: flex;
        align-items: center;
        height: 72px;
        width: 72px;
        left: 519px;
        top: 106px;
        border-radius: 50px;   
    }
    .text {
        position: relative;
        top: 40px;
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 32px;
        text-align: center;
        letter-spacing: -0.128571px;
        color: #5B636D;
    }
    h2 {
        position: relative;
        top: 100px;
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 18px;
        line-height: 22px;
        text-align: center;
        letter-spacing: -0.128571px;
        color: #24303E;
    }
    .profession {
        position: relative;
        top: 90px;
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 14px;
        line-height: 25px;
        text-align: center;
        letter-spacing: -0.1px;
        color: #A7AAAD;
    }
</style>