<template>

    <header class="Header">
        <h1 class="Title">Company Name</h1>

        <div class="Navigation">
            <a @click="goTo('/')" class="NavList">Home</a>
            <a @click="goTo('prices')" class="NavList">Harga Website</a>
            <a @click="goTo('mobile-app')" class="NavList">Aplikasi Mobile</a>
            <a @click="goTo('contact')" class="NavList">Hubungi Kami</a>
            <a @click="goTo('about-us')" class="NavList">Tentang Kami</a>
        </div>

    </header>

</template>

<script>
import router from '../router'
export default {
    methods: {
        goTo (val) {
            router.push(val)
        }
    }
}
</script>

<style scoped>
.Header{
    margin-bottom: 50px;
    display: flex;
    background-color: #79a8a9;
}

.Title {
    flex: 1;
    text-align: start;
    margin: 20px;
    color: #f4f7f7;
}

.Navigation {
    flex: 1;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.NavList {
    text-decoration: none;
    color: #f4f7f7;
    font-size: 1.3em;
}
</style>