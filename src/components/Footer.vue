<template>
<div class="container space-top-bottom">
      <div class="row">
        <div class="col-4">
           <h3>Address</h3>
        <div class="contact">
             <p class="">382 NE 191st ST# 87394 Miami,FL 33179-3899</p>
          </div>
          <div class="contact">
            <p class="">+1(305)547-9909(9am -5pm EST, Monday-Friday)</p>
          </div>
          <div class="contact">
            <p class="">support@maxcoach.com</p>
          </div>
          <div class="d-flex social-icon">
            <i class="fa fa-facebook" aria-hidden="true"></i>
            <i class="fa fa-twitter" aria-hidden="true"></i>
            <i class="fa fa-youtube-play" aria-hidden="true"></i>
            <i class="fa fa-instagram" aria-hidden="true"></i>
            <i class="fa fa-linkedin" aria-hidden="true"></i>
          </div>
        </div>
        <div class="col">
            <ul>
                <li><h3 class="">Explore</h3></li>
                <li class="link" v-for="link, i in exploreLink" :key="i"><a  href="">{{link}}</a></li>
            </ul>
        </div>
        <div class="col pt-4">
            <ul>
               <li class="link" v-for="link, i in middleLink" :key="i"><a  href="">{{link}}</a></li>
            </ul>
        </div>
        <div class="col">
            <ul>
                <li><h3 class="">Information</h3></li>
                <li class="link" v-for="link, i in informationLink" :key="i"><a href="">{{link}}</a></li>
            </ul>
        </div>
      </div>
</div>

</template>

<script>

export default {
  components: { 

  },
  name: "Footer",
  data(){
      return {
          exploreLink: [
              "Start here", "Blog", "About us"
          ],
          middleLink: [
              "Success story", "Courses","Contact us"
          ],
          informationLink: [
              "Membership", "Purchase guide", "Privacy policy", "Terms of service"
          ]
      }
  }
};
</script>

<style lang="scss" scoped>
ul{
    list-style: none;
         a{
            text-decoration: none;
            color: grey;
            }
        }

.social-icon{
    color:lightgray;
       i {
         padding: 0 10px;
        font-size: 20px;
                    /*&:hover {
                        cursor: pointer;
                        color: white;
                    }*/
                }
}
    
    
  

</style>