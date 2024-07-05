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

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  
    .container {
    max-width: 1024px;
    margin: 0 auto;
    display: flex;

    ul li {
            list-style: none;
            margin-left: 10px;
        }

  }
}



</style>
