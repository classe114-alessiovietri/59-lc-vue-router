<script>
export default {
    data() {
        return {

        };
    },
    methods: {
        goToHomePage() {
            this.$router.push({ name: 'home' });
        },
        sum(numOne, numTwo) {
            
        }
    },
    mounted() {
        console.log(this.$route);
    }
}
</script>

<template>
    <div>
        <h1>
            CONTACT PAGE
        </h1>

        <button @click="goToHomePage()">
            Vai alla home page
        </button>
    </div>
</template>

<style lang="scss" scoped>
</style>
