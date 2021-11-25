<template>

    <footer>
        <div class="links-bg">
            <div class="container">
                <!-- link utili -->
                <div class="links">

                    <!-- DC COMICS -->
                    <div>
                        <h1>Dc comics</h1>
                        <ul>
                            <li>characters</li>
                            <li>comics</li>
                            <li>movies</li>
                            <li>tv</li>
                            <li>games</li>
                            <li>videos</li>
                            <li>news</li>
                        </ul>
                    </div>

                    <!-- SHOP -->
                    <div>
                        <h1>Shop</h1>
                        <ul>
                            <li>Shop Dc</li>
                            <li>Shop Dc Collectionables</li>
                        </ul>
                    </div>

                    <!-- DC -->
                    <div>
                        <h1>Dc</h1>
                        <ul>
                            <li>Terms of use</li>
                            <li>privacy policy (new)</li>
                            <li>ad choice</li>
                            <li>advertising</li>
                            <li>jobs</li>
                            <li>subscriptions</li>
                            <li>takent workshops</li>
                            <li>CPSC certificates</li>
                            <li>ratings</li>
                            <li>shop help</li>
                            <li>contact us</li>
                        </ul>
                    </div>

                    <!-- SITES -->
                    <div>
                        <h1>Sites</h1>
                        <ul>
                            <li>DC</li>
                            <li>MAD magazine</li>
                            <li>DC kids</li>
                            <li>DC universe</li>
                            <li>DC power visa</li>
                        </ul>
                    </div>
                </div>

            </div>

        </div>
        
        <div class="contacts-bg">
            <div class="container footer-contact">
                <!-- contatti -->
                <div class="contacts">
                    <a href="">SIGN-UP NOW!</a>
                </div>

                <div class="social">
                    <h2>Follow us</h2>

                    <div class="img-container">
                        <img src="@/assets/footer-facebook.png" alt="">
                    </div>

                    <div class="img-container">
                        <img src="@/assets/footer-twitter.png" alt="">
                    </div>

                    <div class="img-container">
                        <img src="@/assets/footer-youtube.png" alt="">
                    </div>

                    <div class="img-container">
                        <img src="@/assets/footer-pinterest.png" alt="">
                    </div>

                    <div class="img-container">
                        <img src="@/assets/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </footer>

</template>

<script>
export default {
    name : 'Footer'
}
</script>

<style scoped lang="scss">
    @import '@/Style/utilities.scss';
    @import '@/Style/variabili.scss';

    footer {
        background-color: $dark-gray;
        color: white;
        max-height: auto;

        .links-bg {
            background-image: url('../assets/footer-bg.jpg');
            background-repeat: no-repeat;
            background-position: top;
            background-size: cover;
        }

        .links {
            padding: 1rem 0;
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            height: 400px;
            width: 350px;
            div {
                padding: 1rem;
            }
            h1 {
                text-transform: uppercase;
                font-weight: 400;
                padding-bottom: 1rem;
                font-size: 1.2rem;
            }
            ul {
                list-style: none;
                li {
                    color: $gray;
                    font-size: 0.9rem;
                    text-transform: capitalize;
                }
            }
        }

        .footer-contact {
            display: flex;
            align-items: center;
            justify-content: space-between;
            .contacts {
                background-color: $dark-gray;
                padding: 2.5rem 0;
                a {
                    text-decoration: none;
                    color: currentColor;
                    text-transform: uppercase;
                    padding: 0.5rem;
                    border: 2px solid $primary-color;
                }
            }

            .social {
                display: flex;
                align-items: center;
                h2 {
                    color: $primary-color;
                    margin-right: 1rem;
                    text-transform: uppercase;
                }
                .img-container {
                    margin: 0 0.5rem;
                }
            }
        }

    }
</style>