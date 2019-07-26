<template>
    <div id="app">
        <router-view></router-view>
        <FooterGuide v-show='$route.meta.showFooter'/>
    </div>
</template>

<script>
import FooterGuide from './components/FooterGuide/FooterGuide'
export default {
    props: {

    },
    data() {
        return {

        };
    },
    computed: {

    },
    created() {

    },
    mounted() {

    },
    watch: {

    },
    methods: {

    },
    components: {
        FooterGuide
    },
};
</script>

<style lang='stylus' rel='stylesheet/stylus'>
  .app
    width 100%
    height 100%
    background #f5f5f5
</style>
