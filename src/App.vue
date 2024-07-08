<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import AppBlueBanner from './components/AppBlueBanner.vue'

export default{
    components : {
      AppHeader,
      AppFooter,
      AppBlueBanner
    }
}
</script>

<template>
  <AppHeader/>
  <AppBlueBanner/>
  <AppFooter/>
</template>

<style lang="scss">
@use "./styles/general.scss" as *;



</style>
