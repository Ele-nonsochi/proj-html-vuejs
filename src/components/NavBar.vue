<template>
   <div class="container">
      <nav class="nav-bar">
        <img src="@/assets/images/dark-logo.png" alt="logo" />
        <ul>
          <li v-for="(item, i) in navbarChoice" :key="i">
              <a>{{ item.title }} <i class="fa fa-angle-down"></i></a>
         </li>
         <div class="icon-nav">
         <i class="fa fa-shopping-cart" aria-hidden="true"></i>
         <i class="fa fa-user-o"></i>
         </div>
         <input type="search"/>
        </ul>
      </nav>
    </div>
  
</template>

<script>


export default {
  name: "NavBar",
  
    data() {
        return {
             navbarChoice : [
                 {
          title: "Home",
          href: "#",
        },
        {
          title: "Page",
          href: "#prodotti",
        },
        {
          title: "Courses",
          href: "#chi_siamo",
        },
        {
          title: "Features",
          href: "#contatti",
        },
        {
          title: "Blog",
          href: "#contatti",
        },
        {
          title: "Shop",
          href: "#contatti",
        },
        {
          title: "Icon",
          href: "#contatti",
        },
        ]
        }
    }

}

</script>

<style lang="scss">
.bg-color {
  background-color: rgba(233, 230, 227, 255);
  .nav-bar {
    display: flex;
    justify-content: space-between;
    margin: auto;
    align-items: center;
    img{
        width: 150px;
    }
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

.icon-nav{
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 30px;
        }
</style>