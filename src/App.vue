<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import TheBlueBanner from "./components/TheBlueIconBanner.vue"
import comicsData from "./db/comics_data"
import comicCard from "./components/ComicCard.vue"

export default {
  components: {
    TheHeader,
    TheFooter,
    TheBlueBanner,
    comicCard
  },

  data() {
    return {
      comicsData
    }
  }
}
</script>

<template>
  <TheHeader></TheHeader>

  <main>
    <div class="jumbotron"></div>

    <div class="comicsContainer">
      <div class="container">
        <div class="row row-cols-6">
          <div
            class="col" 
            v-for="(comicData, i) in comicsData"
            :key="`comic_${i}`"
          >
            <comicCard :singleComicData="comicData"></comicCard>
          </div>
        </div>
      </div>
    </div>
    
  </main>

  <TheBlueBanner></TheBlueBanner>

  <TheFooter></TheFooter>
</template>

<style lang="scss">
  @use "./styles/partials/variables" as *;

  .comicsContainer {
    background-color: $color_Dark;
    padding: 3rem 0rem;
  }

  .jumbotron {
    min-height: 370px;
    background-image: url("./assets/jumbotron.jpg");
    background-position-y: 5%;
  }
</style>
