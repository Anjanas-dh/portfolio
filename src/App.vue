<template>
    <div id="app">
        <VueHeader></VueHeader>
        <VueContent></VueContent>
        <VueFooter></VueFooter>
    </div>
</template>

<script>
    import VueHeader from './components/VueHeader.vue'
    import VueContent from './components/VueContent.vue'
    import VueFooter from './components/VueFooter.vue'

    export default {
        name: 'app',
        components: {
            VueHeader,
            VueContent,
            VueFooter
        }
    }
</script>

<style lang="scss">
    @import url('https://fonts.googleapis.com/css?family=Noto+Sans+HK|Open+Sans&display=swap');
    @import "styles/core";
</style>
