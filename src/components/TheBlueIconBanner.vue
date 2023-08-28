<script>
    export default {
        
    }
</script>

<template>
    <div class="banner pt-5 pb-5">
        <div class="container">
            <ul class="d-flex justify-content-between">
                <li class="d-flex align-items-center gap-3">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <div class="iconName">DIGITAL COMICS</div>
                </li>

                <li class="d-flex align-items-center gap-3">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <div class="iconName">DC MERCHANDISE</div>
                </li>

                <li class="d-flex align-items-center gap-3">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                    <div class="iconName">SUBSCRIPTION</div>
                </li>

                <li class="d-flex align-items-center gap-3">
                    <img src="../assets/buy-comics-shop-locator.png" alt="" class="locatorIcon">
                    <div class="iconName">COMIC SHOP LOCATOR</div>
                </li>

                <li class="d-flex align-items-center gap-3">
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                    <div class="iconName">DC POWER VISA</div>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use "../styles/partials/variables" as *;

    .banner {
        background-color: $color_Primary;
    }

    ul {
        list-style: none;
        margin: 0;
    }

    img {
        width: 45px;
    }

    .locatorIcon {
        width: 35px;
    }

    .iconName {
        font-size: 0.9rem;
        color: white;
    }
</style>