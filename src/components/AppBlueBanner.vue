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
@use "../styles/partials/_variables" as *;

section {
    background-color: $primary;
    color: white;

    h3{
        font-weight: 400;
        margin-left: -10px;
    }

    .container {
        justify-content: center;
        align-items: center;

        img{
            max-width: 100px;
            transform: scale(0.5);
        }

        div{
            flex-basis: calc(100% / 5);
            display: flex;
            align-items: center;
        }
    }
}

// MEDIA QUERY

@media screen and (max-width:520px) {
    h3 {
        display: none;
    }

    img {
        width: 100%;
    }
}
</style>