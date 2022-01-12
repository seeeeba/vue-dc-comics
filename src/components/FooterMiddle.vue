<template>
    <footer>
        <div class="background">
            <div class="container">
                <ul>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                    <li>list</li>
                </ul>
            </div>
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
    </footer>
</template>

<script>
export default {
    name: "FooterMiddle",
}
</script>

<style scoped lang="scss">
    .background{
        width: 100%;
        height: 400px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        position: relative;
        overflow: hidden;
        img{
            position: absolute;
            right: 50px;
            top: -50px;
            transform: rotate(-20deg);
            width: 30%;
        }
        ul{
            list-style-type: none;
            color: white;
        }
    }
    
</style>