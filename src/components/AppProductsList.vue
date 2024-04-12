<script>
export default {
    name: 'AppProductsList'
}
</script>

<template>
    <div class="products">
        <div class="container">
            <div class="images">
                <div class="dc">
                    <img src="/src/assets/img/buy-comics-digital-comics.png" alt="">
                    <p>DIGITALS COMICS</p>
                </div>
                <div class="dc">
                    <img src="/src/assets/img/buy-comics-merchandise.png" alt="">
                    <p>DC MERCHANDAISE</p>
                </div>
                <div class="dc">
                    <img src="/src/assets/img/buy-comics-subscriptions.png" alt="">
                    <p>SUBSCRIPTION</p>
                </div>
                <div class="dc">
                    <img src="/src/assets/img/buy-comics-shop-locator.png" alt="">
                    <p>COMIC SHOP LOCATOR</p>
                </div>
                <div class="dc">
                    <img src="/src/assets/img/buy-dc-power-visa.svg" alt="">
                    <p>DC POWER VISA</p>
                </div>
            </div>
        </div>
    </div>
</template>/src/assets/img/buy-comics-shop-locator.png

<style scoped lang="scss">
.products {
    background-color: #0282f9;
    padding: 50px;
}

.images {
    display: flex;
    gap: 15px;
    justify-content: center;
}
</style>