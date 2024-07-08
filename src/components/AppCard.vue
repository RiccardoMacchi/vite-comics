<script>
export default {
    name: "AppCard",
    props: {
        singleComic : Object,
    }
    
}
</script>

<template>
    <div class="my_card">
        <img :src="singleComic.thumb" alt="alt">
    </div>
</template>

<style lang="scss">

.my_card {
    flex-basis: calc(100% / 6);
}
</style>