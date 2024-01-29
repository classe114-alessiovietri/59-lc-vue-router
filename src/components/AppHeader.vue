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
    <header>
        <nav>
            <ul>
                <li>
                    <router-link :to="{ name: 'home' }">
                        Home
                    </router-link>
                </li>
                <li>
                    <router-link :to="{ name: 'about' }">
                        Chi siamo
                    </router-link>
                </li>
                <li>
                    <router-link :to="{ name: 'product', params: { id: 1 } }">
                        Rick Sanchez
                    </router-link>
                </li>
                <li>
                    <router-link :to="{ name: 'product', params: { id: 2 } }">
                        Morty Smith
                    </router-link>
                </li>
                <li>
                    <router-link :to="{ name: 'contact' }">
                        Contatti
                    </router-link>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
nav {
    ul {
        display: flex;
        list-style: none;
        justify-content: center;

        li {
            margin: 0 10px;
        }
    }
}
</style>
