<template>
  <div class="main-app flex flex-col items-center ">
    <app-header />
    <app-hero />
    <app-start />
    <app-info />
    <app-more-info />
    <app-reviews />
    <app-footer />
  </div>
</template>

<script>
import appHeader from './components/app-header.vue'
import appHero from './components/app-hero.vue'
import appStart from './components/app-start.vue'
import appInfo from './components/app-info.vue'
import appMoreInfo from './components/app-more-info.vue'
import appReviews from './components/app-reviews.vue'
import AppReviews from './components/app-reviews.vue'
import appFooter from './components/app-footer.vue'
export default {
  components: {
    appHeader,
    appHero,
    appStart,
    appInfo,
    appMoreInfo,
    appReviews,
    AppReviews,
    appFooter
  },
}
</script>

<style lang="scss" scoped>
</style>