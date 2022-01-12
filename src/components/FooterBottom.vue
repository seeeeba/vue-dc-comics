<template>
    <footer>
        <div class="background">
            <div class="container">
                <div class="btn">
                    SIGN-UP NOW!
                </div>

                <ul>
                    <li id="write">
                        FOLLOW US
                    </li>
                    <li>
                        <img src="../assets/img/footer-facebook.png" alt="facebook">
                    </li>
                    <li>
                        <img src="../assets/img/footer-twitter.png" alt="twitter">
                    </li>
                    <li>
                        <img src="../assets/img/footer-youtube.png" alt="youtube">
                    </li>
                    <li>
                        <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                    </li>
                    <li>
                        <img src="../assets/img/footer-periscope.png" alt="facebook">
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "FooterBottom",
}
</script>

<style scoped lang="scss">
@import '../style/general.scss';
    .background{
        background-color: #303030;
        height: 150px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        .btn{
            border: 3px solid #1363ad;
            display: inline-block;
            color: white;
            padding: 15px;
        }
        ul{
            display: flex;
            list-style-type: none;
            float: right;
            align-items: center;
            #write{
                color: white;
                font-weight: bold;
            }
            li{
                margin: 0 5px;
            }
        }
    }
</style>