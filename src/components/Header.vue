<template>
  <header class="bg-color">
    <div class="container">
    <NavBar></NavBar>
      <!--<nav class="nav-bar">
        <img src="@/assets/images/dark-logo.png" alt="logo" />
        <ul>
          <li>Home</li>
          <li>Page</li>
          <li>Courses</li>
          <li>Features</li>
          <li>Blog</li>
          <li>Shop</li>
          <li>Icon</li>
          <li><input type="search" /></li>
        </ul>
      </nav>-->
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
          <div class="col-7 pr-2">
            <img
              src="@/assets/images/home-5-hero-image.png"
              alt="img"
              width="50%"
            />
          </div>
        </div>
      </section>
    </div>
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
  .nav-bar {
    display: flex;
    justify-content: space-between;
    margin: auto;
    align-items: center;
    ul {
      display: flex;
      list-style: none;

      li {
        padding: 10px;
        font-weight: bold;
      }
    }
  }
}
</style>
