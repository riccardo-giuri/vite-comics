<script>
    export default {
        props: {
            singleComicData: Object,
        }
    }
</script>

<template>
    <div class="cardContainer">
        <img :src="singleComicData.thumb" alt="">

        <div class="comicName"> {{ singleComicData.series }}</div>
    </div>
</template>

<style lang="scss" scoped>
    @use "../styles/partials/variables" as *;

    img {
        width: 100%;
        height: 255px;
    }

    .comicName {
        text-transform: uppercase;
        color: white;
        font-weight: bold;
        font-size: 0.75rem;
    }

    .cardContainer {
        margin-bottom: 0.8rem;
    }
</style>