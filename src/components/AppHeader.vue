<script >
export default{
    name: "AppHeader",

    data(){
        return {
            menuHeader : [
                "CHARACTERS",
                "COMICS",
                "MOVIES",
                "TV",
                "GAMES",
                "COLLECTIBLES",
                "VIDEOS",
                "FANS",
                "NEWS",
                "SHOP"
            ],
        }
    }
}

</script>

<template>
    <header>
        <div class="container">
            <a href="#">
                <img src="../assets/dc-logo.png" alt="Logo DC">
            </a>
            <nav>
                <ul>
                    <li v-for="menu in menuHeader"><a href="">{{ menu }}</a></li>
                </ul>
            </nav>
        </div>
    </header>

</template>

<style lang="scss" scoped>
header {
    background-color: white;

    .container {
        align-items: center;

        a {
            text-decoration: none;
            color: black;
            font-weight: 600;
        }

        nav{
            flex-grow: 1;
            text-align: right;

            ul li {
            display: inline-block;
            }
        }
    }

       
}

</style>
