<script>
export default {
    name: "AppBlueBanner",
}

</script>

<template>
    <section>
        <div class="container">
            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="Digital">
                <h3>DIGITAL COMICS</h3>
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="Merch">
                <h3>DC MERCHANDISE</h3>
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="Subscriptions">
                <h3>SUBSCRIPTIONS</h3>
            </div>
            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="Location">
                <h3>COMIC SHOP LOCATOR</h3>
            </div>
            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="Buy">
                <h3>DC POWER VISA</h3>
            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>

section {
    background-color: #0282f9;
    color: white;

    h3{
        font-weight: 400;

    }

    .container {
        justify-content: center;
        align-items: center;

        img{
            transform: scale(0.5);
        }

        div{
            display: flex;
            justify-content: center;
            align-items: center;
        }
    }
}
</style>