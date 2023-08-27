<script>
export default {
    data() {
        return {
            nav_Links: [
                { name: "Characters"},
                { name: "comics"},
                { name: "movies"},
                { name: "tv"},
                { name: "games"},
                { name: "collectibles"},
                { name: "videos"},
                { name: "fans"},
                { name: "news"},
                { name: "shop"}
            ]
        }
    }
}
</script>

<template>
    <div class="container d-flex justify-content-between align-items-center">
        <div class="imgContainer">
            <img src="../assets/dc-logo.png" alt="">
        </div>

        <ul class="nav nav-underline d-flex gap-4">
            <li class="nav-item" v-for="link in nav_Links">
                <a class="nav-link" href="#">{{ link.name.toUpperCase() }}</a>
            </li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
    .nav-link {
        color: black;
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bold;
        font-size: 0.8rem;

        &:hover {
            color: blue;
            border-bottom-color: blue;
        }
    }
</style>