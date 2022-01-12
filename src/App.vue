<template>
  <div id="app">
    <Header />
    <Jumbo />
    <ComicsList />
    <FooterUp />
    <FooterMiddle />
    <FooterBottom />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbo from "./components/Jumbo.vue";
import ComicsList from "./components/ComicsList.vue";
import FooterUp from "./components/FooterUp.vue";
import FooterMiddle from "./components/FooterMiddle.vue";
import FooterBottom from "./components/FooterBottom.vue";

export default {
 name: "App",
  components: {
    Header,
    Jumbo,
    ComicsList,
    FooterUp,
    FooterMiddle,
    FooterBottom
  },
};
</script>

<style scoped lang="scss">
 @import './style/general.scss';
  @import './style/ColorApp.scss';
  @import './style/commun.scss';


  main{
    width: 100%;
    height: 200px;
    background: black;
  }
</style>
