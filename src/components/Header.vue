<template>
    <header>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="Logo principale">
            </div>

            <ul >
                <li v-for="(element, index) in links" :key="index"><a href="">{{ links[index].content }}</a></li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header",
    data: function(){
        return {
            links: [
                {
                    content: 'CHARACTERS',
                    url: '#',
                },
                {
                    content: 'COMICS',
                    url: '#',
                },
                {
                    content: 'MOVIES',
                    url: '#',
                },
                {
                    content: 'TV',
                    url: '#',
                },
                {
                    content: 'GAMES',
                    url: '#',
                },
                {
                    content: 'COLLECT',
                    url: '#',
                },
                {
                    content: 'VIEDO',
                    url: '#',
                },
                {
                    content: 'FANS',
                    url: '#',
                },
                {
                    content: 'NEWS',
                    url: '#',
                },
                {
                    content: 'SHOP',
                    url: '#',
                }
            ],
        }
    }
}
</script>

<style scoped lang="scss">
@import '../style/ColorApp.scss';
    .container{
        width: 100%;
        height: 150px;
        display: flex;
        justify-content: center;
        align-items: center;
        justify-content: space-around;
        img{
            width: 90px;
        }
        ul{
            list-style-type: none;
            display: flex;            
            align-items: center;
            li{
                margin: 0 20px;
                a{
                    padding: 56px 0;
                    text-decoration: none;
                    color: gray;
                    font-weight: bold; 
                    &:hover{
                        border-bottom: 8px solid $color_style;
                    }
                }
            }
        }
    }
</style>