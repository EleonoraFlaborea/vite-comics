<script >
export default {
    name: 'AppCard',
    props: {
        product: Object
    }
};
</script>

<template>
    <div>
        <figure>
            <img :src="product.thumb" :alt="product.series">
        </figure>
        <div class="title">
            <p>{{ product.price }}</p>
            <p>{{ product.series }}</p>
            <p>{{ product.type }}</p>
        </div>


    </div>
</template>

<style lang="scss" scoped>
img {
    width: 100%;
}

div {
    padding: 20px 0;
}

figure {
    width: 150px;
    height: 150px;
}
</style>