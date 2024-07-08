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
        <div>
            <img :src="singleComic.thumb" alt="alt">
        </div>
        
        <h3>{{ singleComic.series }}</h3>
    </div>
</template>

<style lang="scss">

.my_card {
    flex-basis: calc(100% / 6 - 20px);
    div{
        aspect-ratio: 1 / 1;
        overflow: hidden;
    }

    h3 {
        margin: 20px 0;
    }
}
</style>