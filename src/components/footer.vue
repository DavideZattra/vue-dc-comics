<template>
    <footer>

        <section id="upper-footer">

            <nav>

                <h4>Dc comics</h4>

                <ul>

                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a href="#">Games</a>
                    </li>
                    <li>
                        <a href="#">Videos</a>
                    </li>
                    <li>
                        <a href="#">News</a>
                    </li>

                </ul>

                <h4>Shop</h4>

                <ul>

                    <li>
                        <a href="#">Shop DC</a>
                    </li>
                    <li>
                        <a href="#">Shop DC Collectibles</a>
                    </li>
                    
                </ul>
                
                <h4>Dc</h4>

                <ul>

                    <li>
                        <a href="#">Terms Of Use</a>
                    </li>
                    <li>
                        <a href="#">Privacy Policy (New)</a>
                    </li>
                    <li>
                        <a href="#">Ad Choices</a>
                    </li>
                    <li>
                        <a href="#">Advertising</a>
                    </li>
                    <li>
                        <a href="#">Jobs</a>
                    </li>
                    <li>
                        <a href="#">Subscriptions</a>
                    </li>
                    <li>
                        <a href="#">Talent Workshops</a>
                    </li>
                    <li>
                        <a href="#">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="#">Ratings</a>
                    </li>
                    <li>
                        <a href="#">Shop Help</a>
                    </li>
                    <li>
                        <a href="#">Contact Us</a>
                    </li>                 

                </ul>
                
                <h4>Sites</h4>

                <ul>

                    <li>
                        <a href="#">DC</a>
                    </li>
                    <li>
                        <a href="#">MAD Magazine</a>
                    </li>
                    <li>
                        <a href="#">DC Kids</a>
                    </li>
                    <li>
                        <a href="#">DC Universe</a>
                    </li>
                    <li>
                        <a href="#">DC Power Visa</a>
                    </li>

                </ul>
                
            </nav>

            <img src="../assets/img/dc-logo-bg.png" alt="Big Dc Logo">

        </section>
        <section id="lower-footer">

            <button>Sign up now!</button>

            <nav>

                <h4>Follow us</h4>

                <ul>

                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img class="social-logo" src="" alt=""></a>
                    </li>

                </ul>

            </nav>

        </section>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
@import '../style/general.scss';
@import '../style/variables.scss';

    ul{
        list-style: none;

        li>a{
            text-decoration: none;
            color: $linkColor;
        }
    }

    h4{
        color: white;
    }

    #upper-footer{
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;

    }

</style>