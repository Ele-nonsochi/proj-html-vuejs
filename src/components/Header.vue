<template>
<header class="container bg-color">
    <NavBar></NavBar>
  <section class="container-hero space-top-bottom text-center">
        <div class="row">
          <div class="col-5 content-position text-start">
            <h1 class="">Complete your Dreams in JavaS Programming</h1>
            <p class="p-2">
              Learn any coding program in distance and for a reasonable free.
              You don't have to struggle alone, you've got our assistance and
              help.
            </p>
            <a href="#" class="button-page"><i class="fa fa-download"></i> Downloand free E-book</a>
          </div>
          <div class="col-7 pr-2 container-icon-over">
            <img src="@/assets/images/home-5-hero-image.png" alt="img" width="50%" />
            <div class="icon-position d-flex flex-column">
            <i class="fa fa-file-o" aria-hidden="true"></i>
            <i class="fa fa-life-ring" aria-hidden="true"></i>
            <i class="fa fa-book" aria-hidden="true"></i>
            <i class="fa fa-shopping-cart" aria-hidden="true"></i>
            </div>
          </div>
        </div>
  </section>
</header>

</template>

<script>
import NavBar from "./NavBar.vue"

export default {
  name: "Header",
  components: {
    NavBar,
  },
};
</script>

<style lang="scss">
.bg-color {
  background-color: rgba(233, 230, 227, 255);
}
.container-icon-over{
  margin: 0 auto;
  position: relative;
}

.icon-position{
    position: absolute;
    bottom: 70%;
    right: -2%;
    transform: translate(0%, -50%);
    width: 40px;
    height: 60px;
    background-color: white;
    padding-bottom: 5px;
    padding-top: 5px;
    
    .fa{ margin-right:0;
         padding-bottom: 5px;
         font-size: 20px;
         background-color: white;
         }
}
</style>

/**Hover bottone , capire se fare un div prima del'header per il bg */
