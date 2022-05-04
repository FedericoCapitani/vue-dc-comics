<template>
    <div class="footer">
        <div class="shop">
            <div class="shop-card">
                <img src="@/assets/img/buy-comics-digital-comics.png" alt="digital comics shop">
                <p>
                    DIGITAL COMICS
                </p>
            </div>
            <div class="shop-card">
                <img src="@/assets/img/buy-comics-merchandise.png" alt="merchandise shop">
                <p>
                    DC MERCHANDISE
                </p>
            </div>
            <div class="shop-card">
                <img src="@/assets/img/buy-comics-subscriptions.png" alt="subscriptions shop">
                <p>
                    SUBSCRIPTION
                </p>
            </div>
            <div class="shop-card">
                <img src="@/assets/img/buy-comics-shop-locator.png" alt="comics shop locator tool">
                <p>
                    COMIC SHOP LOCATOR
                </p>
            </div>
            <div class="shop-card">
                <img src="@/assets/img/buy-dc-power-visa.svg" alt="dc power visa" class="small-img">
                <p>
                    DC POWER VISA
                </p>
            </div>
        </div>
        <div class="info">
            <div class="link-container">
                <div class="comics">
                    <h3>DC COMICS</h3>

                    <p>Characters</p>
                    <p>Comics</p>
                    <p>Movies</p>
                    <p>TV</p>
                    <p>Games</p>
                    <p>Videos</p>
                    <p>News</p>

                    <h3>SHOP</h3>

                    <p>Shop DC</p>
                    <p>Shop DC Collectibles</p>

                </div>
                <div class="DC">
                    <h3>DC</h3>

                    <p>Terms Of Use</p>
                    <p>Privacy policy (New)</p>
                    <p>Ad Choices</p>
                    <p>Advertising</p>
                    <p>Jobs</p>
                    <p>Subscriptions</p>
                    <p>Talent Workshops</p>
                    <p>CPSC Certificates</p>
                    <p>Ratings</p>
                    <p>Shop Help</p>
                    <p>Contact Us</p>
                </div>
                <div class="sites">
                    <h3>SITES</h3>

                    <p>DC</p>
                    <p>MAD Magazines</p>
                    <p>DC Kids</p>
                    <p>DC Universe</p>
                    <p>DC Power Visa</p>
                </div>
            </div>
            <div class="container-img">
                
            </div>
        </div>
        <div class="social">
            <div class="sign-up">
                SIGN UP NOW!
            </div>
            <div class="social-links">
                <p>FOLLOW US</p>
                <img src="@/assets/img/footer-facebook.png" alt="facebook icon">
                <img src="@/assets/img/footer-twitter.png" alt="twitter icon">
                <img src="@/assets/img/footer-youtube.png" alt="youtube icon">
                <img src="@/assets/img/footer-pinterest.png" alt="pinterest icon">
                <img src="@/assets/img/footer-periscope.png" alt="periscope icon">
            </div>
        </div>
    </div>
</template>

<style scoped>
    .shop{
        background-color: #0282f9;
        display: flex;
        padding: 2rem 15%;
        justify-content: space-between;
    }
    .shop-card{
        display: flex;
        align-items: center;
        column-gap: 1rem;
    }
    .shop-card img{
        max-height: 70px;
    }
    .shop-card p{
        color: white;
        font-weight: 700;
    }
    .small-img{
        max-width: 60px;
    }
    .info{
        background-image: url('@/assets/img/footer-bg.jpg');
        background-size: cover;
        padding: 0 15%;
        display: flex;
        justify-content: space-between;
        max-height: 450px;
    }
    .link-container{
        display: flex;
        column-gap: 2rem;
        padding: 3rem 0;
    }
    .link-container h3{
        color: white;
        padding: 1rem 0;
        font-size: 1.3rem;
    }
    .link-container p{
        color: gray;
        padding: 2px 0;
    }
    .container-img{
        height: 450px;
        width: 560px;
        background-image: url('@/assets/img/dc-logo-bg.png');
        background-position: center;
    }
    .social{
        background-color: #303030;
        display: flex;
        justify-content: space-between;
        padding: 3rem 15%;
        align-items: center;
    }
    .sign-up{
        padding: 1.5rem;
        border: 2px solid #0282f9;
        color: white;
        font-size: 1.5rem;
    }
    .social-links{
        display: flex;
        align-items: center;
        column-gap: 1rem;
    }
    .social-links p{
        color: #0282f9;
        font-size: 1.5rem;
        font-weight: 700;
    }
</style>