<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
// Supports weights 300-800
import '@fontsource-variable/open-sans';



export default {
    name: 'MyApp',
    components: {
        AppHeader,
        AppMain,
        AppFooter
    }
}
</script>

<template>
    <AppHeader />
    <AppMain />
    <AppFooter />
</template>

<style lang="scss">
@use './assets/scss/style.scss';
</style>
