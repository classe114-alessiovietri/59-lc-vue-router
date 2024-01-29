<script>
export default {
    data() {
        return {

        };
    },
    methods: {

    }
}
</script>

<template>
    <main>
        <!-- 
            Questo componente (importato globalmente grazie all'installazione del pacchetto vue-router)
            mi consente di avere, per URL diversi, contenuti informativi diversi
        -->
        <router-view></router-view>
    </main>
</template>

<style lang="scss" scoped>
</style>
