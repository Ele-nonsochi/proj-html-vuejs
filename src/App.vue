<template>
 <div>
  <Header></Header>
  <MainBlock1></MainBlock1>
  <MainBlock2></MainBlock2>
  <Footer></Footer>
 </div>
</template>

<script>
import Header from "./components/Header.vue";
import MainBlock1 from "./components/MainBlock1.vue";
import MainBlock2 from "./components/MainBlock2.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    MainBlock1,
    MainBlock2,
    Footer,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "~font-awesome/css/font-awesome.min.css";
@import "style/utilities.scss";
//@import "~font-awesome/css/font-awesome.css";

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
