<template>
    <div>
        <nav class="navbar bg-white border-bottom navbar-light">
            <router-link class="navbar-brand mr-auto" v-bind:to="{name: 'home'}">LaravelBnb</router-link>
            <router-link class="btn nav nav-btn" :to="{name: 'second'}">Second</router-link>
        </nav>
        <div class="container mt-4 mb-4 pr-4 pl-4">
            <router-view></router-view>
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
