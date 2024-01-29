<script>
import axios from 'axios';

export default {
    data() {
        return {

        };
    },
    updated() {
        console.log(this.$route);
        axios.get('https://rickandmortyapi.com/api/character/' + this.$route.params.id)
            .then(response => {
                console.log(response.data)
            })
            .catch(err => {
                this.$router.push({ name: 'not-found' });
            });
    }
}
</script>

<template>
    <div>
        <h1>
            PRODUCT PAGE
        </h1>
    </div>
</template>

<style lang="scss" scoped>
</style>
