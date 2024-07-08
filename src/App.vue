<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import AppBlueBanner from './components/AppBlueBanner.vue'
import AppWrapCard from './components/AppWrapCard.vue'

export default{
    components : {
      AppHeader,
      AppFooter,
      AppBlueBanner,
      AppWrapCard,
    }
}
</script>

<template>
  <AppHeader/>
  <AppWrapCard/>
  <AppBlueBanner/>
  <AppFooter/>
</template>

<style lang="scss">
@use "./styles/general.scss" as *;



</style>
