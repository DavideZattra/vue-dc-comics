<template>
    <main>
        <section id="main-content">
            <h3>-- -- Content goes here -- -- </h3>
        </section>
        <ShopSection />
    </main>
</template>

<script>
import ShopSection from './shop.vue'

export default {
    name: 'Main',
    components : {
        ShopSection
    }
}
</script>

<style lang="scss" scoped>
@import '../style/general.scss';
@import '../style/variables.scss';

#main-content{

    padding: 40px 150px;
    background-color: $contentBgColor;
    color: $whiteMainColor;
}

</style>