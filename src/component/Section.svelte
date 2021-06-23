<script>  
    let srcEgg = '././img/image-transform.jpg'; 
    let srcCup = '././img/image-stand-out.jpg';
    let srcCherry = '././img/image-graphic-design.jpg';
    let srcMandarin = '././img/image-photography.jpg';
</script>

<section>
    <div class='sec1'>
        <h2>Transform your brand</h2>
        <p class='text1'>We are a full-service creative agency specializing in<br />
            helping brands grow fast. Engage your clients through<br />
            compelling visuals that do most of the marketing for you.</p>
        <div class='underline-yellow'>
            <p class='text2'>LEARN MORE</p>
            <div class='line-yellow'></div>
        </div>
    </div >
    <img class='sec2' src={srcEgg} alt='EggPhoto'>
    <img class='sec3' src={srcCup} alt='CupPhoto'>
    <div class='sec4'>
        <h2>Stand out to the right audience</h2>
        <p class='text1'>Using a collaborative formula of designers, researchers,<br />
            photographers, videographers, and copywriters, we’ll<br />
            build and extend your brand in digital places. </p>
        <div class='underline-red'>
            <p class='text2'>LEARN MORE</p>
            <div class='line-red'></div>
        </div>
    </div>
    <div class='sec5'>
        <img src={srcCherry} class='srcCherry' alt='CherryPhoto'>
        <div class='sec5-text'>
            <h3 class='h3-1'>Graphic Design</h3>
            <p class='text3'>Great design makes you memorable. We deliver<br />
                artwork that underscores your brand message<br />
                and captures potential clients’ attention.</p>
        </div>
    </div>
    <div class='sec6'>
        <img src={srcMandarin} class='srcMandarin' alt='MandarinPhoto'>
        <div class='sec6-text'>
            <h3 class='h3-2'>Photography</h3>
            <p class='text4'>Increase your credibility by getting the most<br /> 
            stunning, high-quality photos that improve your<br /> 
            business image.</p>
        </div>
    </div>
</section>

<style>
    section {
        position: relative;
        display: grid;
        grid-template-columns: 720px 720px;
        grid-template-rows: 600px 600px 600px;
        grid-gap: 0 0; 
        height: 1800px;
        width: 1440px;
        }
    .sec1 {
        position: relative;
        display: flex;
        flex-direction: column;
        height: 285px;
        width: 445px;
        left: 165px;
        top: 120px;
    }
    .sec2 {
        left: 720px;
        top: 800px;
    }
    .sec3 {
        left: 0px;
        top: 1400px;
    }
    .sec4 {
        position: relative;
        display: flex;
        flex-direction: column;
        height: 286px;
        width: 445px;
        left: 110px;
        top: 130px;
    }
    .sec5 {
        position: relative;
        left: 0px;
        top: 0px;
    }
    .sec5-text {
        position: relative;
        height: 143px;
        width: 339px;
        left: 191px;
        top: -232px;
    }
    .sec6 {
        position: relative;
        left: 0px;
        top: 0px;
    }
    .sec6-text {
        position: relative;
        height: 143px;
        width: 734px;
        left: 0px;
        top: -232px;
    }
    h2 {
        left: 165px;
        top: 940px;
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 40px;
        line-height: 49px;
        letter-spacing: -0.285714px;
        color: #24303E;
    }
    .h3-1 {
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 28px;
        line-height: 35px;
        text-align: center;
        letter-spacing: -0.2px;
        color: #24554A;
    }
    .h3-2 {
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 28px;
        line-height: 35px;
        text-align: center;
        letter-spacing: -0.2px;
        color: #052C3B;
    }
    .text1 {
        position: relative;
        left: 0px;
        top: -18px;
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        line-height: 30px;
        letter-spacing: -0.128571px;
        color: #808397;
    }
    .text2 {
        position: relative;
        left: 0px;
        top: -8px;
        display: flex;
        align-self: flex-start;
        font-family: 'Fraunces', serif;
        font-style: normal;
        font-weight: 900;
        font-size: 15px;
        line-height: 25px;
        letter-spacing: 1px;
        color: #24303E;
    }
    .line-yellow {
        position: relative;
        left: 0px;
        top: -10px;
        margin-top: -25px;
        margin-left: -8px;
        width: 135px;
        height: 10px;
        background: rgba(250, 212, 0, 0.2);
        border-radius: 10px;
        z-index: -1;
    }
    .underline-yellow:hover .line-yellow {
        cursor: pointer;
        background: rgba(250, 212, 0, 1);   
    }
    .line-red {
        position: relative;
        left: 0px;
        top: -10px;
        margin-top: -25px;
        margin-left: -8px;
        width: 135px;
        height: 10px;
        background: rgb(248, 212, 207);
        border-radius: 10px;
        z-index: -1;
    }
    .underline-red:hover .line-red {
        cursor: pointer;
        background: rgba(254, 119, 102, 1);
    } 
    .text3 {
        top: 100px;
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
        line-height: 27px;
        text-align: center;
        letter-spacing: -0.114286px;
        color: #24554A;  
    }
    .text4 {
        font-family: 'Barlow', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
        line-height: 27px;
        text-align: center;
        letter-spacing: -0.114286px;
        color: #19536C;
    }
</style>