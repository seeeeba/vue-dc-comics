<template>
    <div class="principale">
        <img :src="element.thumb" :alt="element.series">

        <div class="title">
            {{ element.series.toUpperCase() }}
        </div>
    </div>
</template>

<script>
export default {
    name: 'SingleComic',
    props:['element'],
}
</script>

<style lang="scss" scoped>
    .principale{
        width: calc(100% / 7);
        margin: 10px;
    }
    .title{
        color: white;
    }
</style>