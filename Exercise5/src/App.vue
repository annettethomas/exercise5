<template>
    <div class="container">

        <header-shared></header-shared>

        <hr>
        <div class="row">

            <server-comp></server-comp>

            <serverde-comp></serverde-comp>
        </div>
        <hr>

        <footer-shared></footer-shared>
    </div>
</template>

<script>
    import Header from './shared/Header.vue'
    import Footer from './shared/Footer.vue'
    import Server from './components/Server.vue'
    import ServerDetails from './components/ServerDetails.vue'

    export default {
        components: {
            'header-shared': Header,
            'footer-shared': Footer,
            'server-comp': Server,
            'serverde-comp': ServerDetails
        }
    }
</script>

<style>

</style>
