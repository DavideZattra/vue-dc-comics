<template>
    <section id="shop-section">
        <nav>
            <ul>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <p>digital comics</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <p>dc merchandise</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <p>subscription</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <p>comic shop locator</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <p>dc power visa</p>
                    </a>
                </li>
            </ul>
        </nav>
    </section>
</template>

<script>
export default {
    name : 'ShopSection'
}
</script>

<style lang="scss" scoped>
@import '../style/general.scss';
@import '../style/variables.scss';
ul{
    list-style: none;

    li>a{
        text-decoration: none;
        color : $whiteMainColor;
        text-transform: uppercase;
    }
}

#shop-section{
    background-color: $mainBlueColor;
    color : $whiteMainColor;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;

    ul{
        display: flex;
        align-items: center;
            padding: 15px 155px;
        a{
            display: flex;
            align-items: center;
            margin: 0 15px;
            

            img{
                height: 75px;
            }

            p{
                margin-left: 10px;
                font-size: 0.5rem;
            }
        }
    }
}

</style>