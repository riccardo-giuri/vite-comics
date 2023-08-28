<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import TheBlueBanner from "./components/TheBlueIconBanner.vue"

export default {
  components: {
    TheHeader,
    TheFooter,
    TheBlueBanner
  }
}
</script>

<template>
  <TheHeader></TheHeader>

  <main></main>

  <TheBlueBanner></TheBlueBanner>

  <TheFooter></TheFooter>
</template>

<style scoped>

</style>
