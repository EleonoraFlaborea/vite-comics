<script >
import AppCard from './AppCard.vue';
export default {
    name: 'AppMain',
    props: {
        products: Array
    },
    components: { AppCard }
};
</script>

<template>
    <!--MAIN-->
    <main>
        <section class="main-section" id="products">
            <AppCard v-for="(product, i) in  products " :key="i" :product="product" />
        </section>
    </main>
</template>

<style lang="scss" scoped>
.main-section {
    background-color: #1C1C1C;
    min-height: 150px;
    color: white;

    display: flex;
    flex-wrap: wrap;
    justify-content: center;



    div {
        flex-basis: calc(100% / 6);
        display: flex;
        justify-content: center;
        flex-wrap: wrap;

        p {
            flex-basis: 70%;
        }
    }
}
</style>