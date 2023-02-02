<script>

export default {
    name: "AppFooter",
}

</script>

<template>

    <footer>
        <div class="h-footer">

            <div class="footer-menu">

                <div class="first">
                    <ul>
                        <li>Dc Comics</li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Collectibles</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">Fans</a></li>
                        <li><a href="#">News</a></li>
                    </ul>

                    <ul>
                        <li>Shop</li>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="second">
                    <ul>
                        <li>Dc</li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Collectibles</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">Fans</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                </div>

                <div class="third">
                    <ul>
                        <li>Sites</li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                    </ul>
                </div>
            </div>
            <div class="img-big">
                <img src="../assets/img/dc-logo-bg.png" alt="">

            </div>



        </div>

        <div class="l-footer">
            <div class="signup">
                <p>Sign-up Now</p>

            </div>
            <div class="social">
                <p>Follow us</p>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>

            </div>
        </div>



    </footer>




</template>

<style lang="scss" scoped>
footer {

    .h-footer {

        background-image: url(../assets/img/footer-bg.jpg);
        height: 45vh;
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;

        .footer-menu {

            width: 60%;
            margin: 0 auto;
            display: flex;
            margin: 3em;

            .first,
            .second,
            .third {
                width: calc(100%/3);

                ul {

                    li:first-child {
                        text-transform: uppercase;
                        color: white;
                        font-weight: bold;
                        padding-bottom: 0.5em;
                    }

                    li:last-child {
                        padding-bottom: 1.5em;
                    }

                    li {
                        list-style: none;
                        padding: 0.1em 0;

                        a {
                            text-decoration: none;
                            padding-bottom: 0.1em;
                            color: grey;
                            font-size: 0.9em;
                        }
                    }
                }
            }

            .img-big {
                width: 100%;
                height: 100%;

                img {
                    width: 100%;
                    height: 100%;
                }

            }

        }

    }



    .l-footer {
        padding: 2em 5em;
        background-color: #353535;
        height: 10vh;
        display: flex;
        justify-content: space-between;

        .social {
            display: flex;

            ul {

                li {
                    list-style: none;
                }

            }

        }

        .signup p {
            color: white;
            text-transform: uppercase;
            border: 2px solid rgb(36, 104, 187);
            padding: 0.3em;
        }

    }



}
</style>