<template>
    <div class="footer">
        <div class="shop">
            <div class="shop-card" v-for="item in banner" :key="item.id">
                <img :src="item.src" alt="digital comics shop" :class="item.id == 5 ? 'small-img': ''">
                <p>
                    {{item.text}}
                </p>
            </div>
        </div>
        <div class="info">
            <div class="link-container">
                <div v-for="({title, links}, index) in linkgroups" :key="index">
                    <h3> {{title}} </h3>
                <ul>
                    <li v-for="link in links" :key="link.id">
                        <a :href="link.href"> {{link.text}} </a>
                    </li>
                </ul>
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

<style lang="scss" scoped>
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
    .link-container a{
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
        background-color: $dc-footer;
        display: flex;
        justify-content: space-between;
        padding: 3rem 15%;
        align-items: center;
    }
    .sign-up{
        padding: 1.5rem;
        border: 2px solid $dc-primary;
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

<script>
export default {
    name: 'FooterComponent',
    data(){
        return {
            banner: [
                {
                    id: 1,
                    src: require('@/assets/img/buy-comics-digital-comics.png'),
                    text: 'Digital Comics'
                },
                {
                    id: 2,
                    src: require('@/assets/img/buy-comics-merchandise.png'),
                    text: 'DC Merchandise'
                },
                {
                    id: 3,
                    src: require('@/assets/img/buy-comics-subscriptions.png'),
                    text: 'Subscritions'
                },
                {
                    id: 4,
                    src: require('@/assets/img/buy-comics-shop-locator.png'),
                    text: 'Comics Shop Locator'
                },
                {
                    id: 5,
                    src: require('@/assets/img/buy-dc-power-visa.svg'),
                    text: 'DC Power Visa'
                }
            ],
            linkgroups: [
                {
                    title: 'DC COMICS',
                    links: [
                        {
                            id: 1,
                            href: '#',
                            text: 'Characters'
                        },
                        {
                            id: 2,
                            href: '#',
                            text: 'Comics'
                        },
                        {
                            id: 3,
                            href: '#',
                            text: 'Movies'
                        },
                        {
                            id: 4,
                            href: '#',
                            text: 'TV'
                        },
                        {
                            id: 5,
                            href: '#',
                            text: 'Games'
                        },
                        {
                            id: 6,
                            href: '#',
                            text: 'Videos'
                        },
                        {
                            id: 7,
                            href: '#',
                            text: 'News'
                        },
                    ]
                },
                {
                    title: 'SHOP',
                    links: [
                        {
                            id: 1,
                            href: '#',
                            text: 'Shop DC'
                        },
                        {
                            id: 2,
                            href: '#',
                            text: 'Shop DC Collectibles'
                        }
                    ]
                },
                {
                    title: 'DC ',
                    links: [
                        {
                            id: 1,
                            href: '#',
                            text: 'Terms Of Use'
                        },
                        {
                            id: 2,
                            href: '#',
                            text: 'Privacy policy (New)'
                        },
                        {
                            id: 3,
                            href: '#',
                            text: 'Ad Choices'
                        },
                        {
                            id: 4,
                            href: '#',
                            text: 'Advertising'
                        },
                        {
                            id: 5,
                            href: '#',
                            text: 'Jobs'
                        },
                        {
                            id: 6,
                            href: '#',
                            text: 'Subscriptions'
                        },
                        {
                            id: 7,
                            href: '#',
                            text: 'Talent Workshops'
                        },
                        {
                            id: 8,
                            href: '#',
                            text: 'CPSC Certificates'
                        },
                        {
                            id: 9,
                            href: '#',
                            text: 'Ratings'
                        },
                        {
                            id: 10,
                            href: '#',
                            text: 'Shop Help'
                        },
                        {
                            id: 11,
                            href: '#',
                            text: 'Contact Us'
                        }
                    ]
                },
                {
                    title: 'DC COMICS',
                    links: [
                        {
                            id: 1,
                            href: '#',
                            text: 'DC'
                        },
                        {
                            id: 2,
                            href: '#',
                            text: 'MAD Magazines'
                        },
                        {
                            id: 3,
                            href: '#',
                            text: 'DC Kids'
                        },
                        {
                            id: 4,
                            href: '#',
                            text: 'DC Universe'
                        },
                        {
                            id: 5,
                            href: '#',
                            text: 'DC PowerVisa'
                        }
                    ]
                }


            ]
        }
    }
}
</script>