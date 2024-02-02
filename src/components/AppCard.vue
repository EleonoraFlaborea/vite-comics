<script >
export default {
    name: 'AppCard',
    props: {
        products: Object
    }
};
</script>

<template>
    <section class="main-section" id="products">
        <AppCard v-for="(product, i) in products" />
    </section>
</template>

<style lang="scss" scoped>
figure {
    flex-basis: calc(100% / 6);
    display: flex;
    justify-content: center;
    flex-wrap: wrap;

    p {
        flex-basis: 70%;
    }
}
</style>