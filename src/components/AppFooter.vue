<script >
export default{
    name: "AppFooter"
}

</script>

<template>
    <footer>
        <section>
            <div class="container">
                <div class="footer_list">
                    <ul>
                        <li>
                            DC COMICS
                        </li>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                    <ul>
                        <li>SHOP</li>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Collectibles</a></li>
                    </ul>
                    
                </div>
                <div class="footer_list">
                    <ul>
                        <li>DC</li>
                        <li><a href="">Terms Of Use</a></li>
                        <li><a href="">Privacy policy (New)</a></li>
                        <li><a href="">Ad Choices</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="footer_list">
                    <ul>
                        <li>SITES</li>
                        <li><a href="">DC</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
        </section>
        <div class="container flexed"> 
            <div id="sing_up">
                <a href="">SING-UP NOW!</a>
            </div>
            <h4>FOLLOW US</h4>
            <div class="icons">
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use "../styles/partials/_variables" as *;

footer {
    background-color: #303030;

    section {
        background-image: url(../assets/footer-bg.jpg);
        color: white;

        .footer_list {
            padding: 40px 10px;
        }    
        .container {
            background-image: url(../assets/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-position: right;
        }

        a{
            color: #797c81;
        }
    }

    #sing_up {
        flex-grow: 1;
        a {
            color: white;
            font-weight: 600px;
            padding: 10px;
            border: 1px solid $primary;
        }
    }

    .flexed {
        justify-content: flex-end;
        align-items: center;
        padding: 30px 0;
    }

    img {
        margin: 10px;
    }

    h4 {
        display: inline-block;
        margin-right: 20px;
        color: $primary;
    }
    .icons {
        text-align: center;
    }
    
}

@media screen and (max-width:560px) {

    .flexed{
        gap: 15px;

        .icons {
            flex-grow: 1;
        }
    }
}

</style>
