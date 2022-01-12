<template>
    <div class="jumbo">
        <h3>CURRENT SERIES</h3>
    </div>
    
</template>

<script>
export default {
    name: "Jumbo"
}
</script>

<style lang="scss" scoped>
@import '../style/ColorApp.scss';
    .jumbo{
        background-image: url(../assets/img/jumbotron.jpg);
        height: 500px;
        position: relative;
        h3{
            color: white;
            background: $color_style;
            display: inline-block;
            padding: 20px;
            position: absolute;
            bottom: -30px;
            left: 290px;
        }
    }
</style>