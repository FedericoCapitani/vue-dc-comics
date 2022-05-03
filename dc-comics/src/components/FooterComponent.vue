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
                <img src="@/assets/img/buy-dc-power-visa.svg" alt="dc power visa">
                <p>
                    DC PWER VISA
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .shop{
        background-color: blue;
        display: flex;
        padding: 2rem 15%;
        justify-content: space-between;
    }
    .shop-card{
        display: flex;
        align-items: center;
        column-gap: 1rem;
    }
    .shop-card p{
        color: white;
        font-weight: 700;
    }
</style>