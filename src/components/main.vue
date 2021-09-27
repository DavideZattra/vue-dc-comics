<template>
    <main>
        <section id="jumbotron"></section>
        <section id="main-content">
            <div class="label">
                <h4>current series</h4>
            </div>
            <div class="comic-container">
                <div class="comic-cover" v-for='(element, index) in Comics' :key='index'>
                    <img :src="element.thumb" :alt="element.series">
                    <p>{{ element.series }}</p>
                </div>
            </div>
            <button>Load more</button>
        </section>
        <ShopSection />
    </main>
</template>

<script>
import ShopSection from './shop.vue'
import Comics from '../data/comics.js'

export default {
    name: 'Main',
    components : {
        ShopSection,
    },
    data : function(){
        return {
            Comics
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../style/general.scss';
@import '../style/variables.scss';

#jumbotron{
    background-image: url(../assets/img/jumbotron.jpg);
    background-position: top;
    background-repeat: no-repeat;
    height: 400px;
}

#main-content{
    position: relative;
    padding: 40px 150px;
    background-color: $contentBgColor;
    color: $whiteMainColor;
    
    .label{
        position: absolute;
        top: -12.5px;
        height: 40px;

        display: inline-block;
        background-color: $mainBlueColor;
        padding: 0 15px;

        h4{
            font-size: 1rem;
            text-transform: uppercase;
            line-height: 40px;
        }
    }


    .comic-container{
        display: flex;
        flex-wrap: wrap;
        
        .comic-cover{
            flex-basis: calc(100% / 6);
            padding: 10px;
            margin-bottom: 15px;

            img{
                width: 100%;
                height: 150px;
                object-fit: cover;
                object-position: top;
    
            }
    
            p{
                font-size: 0.8rem;
                font-weight: 600;
            }
        }
    }

    button{
        color: $whiteMainColor;
        background-color: $mainBlueColor;
        border: none;
        text-transform: uppercase;
        font-weight: 600;
        font-size: 0.9rem;

        padding: 10px 50px;
    }
}


</style>