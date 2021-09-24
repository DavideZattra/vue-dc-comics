<template>
    <header>
        <section>
            <nav id="main-navbar">
                <div class="main-logo">
                    <a href="#">
                        <img src="../assets/img/dc-logo.png" alt="main-dc-logo">
                    </a>
                </div>

                <ul>

                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li class="active">
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">tv</a>
                    </li>
                    <li>
                        <a href="#">games</a>
                    </li>
                    <li>
                        <a href="#">collectibles</a>
                    </li>
                    <li>
                        <a href="#">videos</a>
                    </li>
                    <li>
                        <a href="#">fans</a>
                    </li>
                    <li>
                        <a href="#">news</a>
                    </li>
                    <li>
                        <a href="#">shop</a>
                    </li>

                </ul>


            </nav>
        </section>
    </header>
</template>

<script>
export default {
    name: 'Header'
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


#main-navbar{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100px;

    .main-logo{
        padding: 7.5px;
        img{
            width: 75px;
        }
        
    }

    ul{
        display: flex;
        justify-content: space-around;
        flex-basis: calc(100% / 2);
        height: 100%;

        a{
            text-transform: uppercase;
            font-size: 0.85rem;
            font-weight: 600;
            color: black;
            line-height: 100px;
        }

        .active{
            border-bottom: 4px solid $mainBlueColor;
            a{
                color: $mainBlueColor;
            }
        }
    }
}
</style>