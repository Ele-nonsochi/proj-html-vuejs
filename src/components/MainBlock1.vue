<template>
<div>
<!--Sezione sotto l'header-->
<section class="container py-5">
     <div class="text-center">
        <h4>STAR LEARNING CODING LANGUAGES</h4>
        <h1 class="">Build Your Dream <span class="word-green">TODAY</span></h1>
     </div>
<div class="container space-top-bottom">
    <div class="row d-flex flex-wrap">
        <div class="col text-center">
            <div class="card card-style">
                <img src="@/assets/images/home-5-image-box-01.png" alt="image"  class="card-img-top">
                <div class="card-block">
                    <h3 class="card-title pt-2">Idea Discussion</h3>
                    <p class="card-text">Get teamed up with the specialists who work and teach coding for years at famous universites.</p>
                    <a class="start-icon">Start now <i class="fa fa-long-arrow-right" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
        <div class="col text-center">
            <div class="card card-style">
                <img src="@/assets/images/home-5-image-box-02.png" alt="image" class="card-img-top">
                <div class="card-block">
                    <h3 class="card-title pt-2">Web Development</h3>
                    <p class="card-text">Learn to start building a webpage from scratch. Yuo decide your own pace, course and speed.</p>
                    <a class="start-icon">Start now <i class="fa fa-long-arrow-right" aria-hidden="true"></i> </a>
                </div>
            </div>
        </div>
         <div class="col text-center">
            <div class="card card-style">
                <img src="@/assets/images/home-5-image-box-03.png" alt="image" class="card-img-top">
                <div class="card-block">
                    <h3 class="card-title pt-2">System Administration</h3>
                    <p class="card-text">Learners are encouraged to study the mechanism and structure of system administration.</p>
                    <a class="start-icon">Start now <i class="fa fa-long-arrow-right" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
         <div class="col text-center">
            <div class="card card-style">
                <img src="@/assets/images/home-5-image-box-04.png" alt="image" class="card-img-top">
                <div class="card-block">
                    <h3 class="card-title pt-2">Graphic Design</h3>
                    <p class="card-text">Have a passion for graphics and arts? Show your talents with confidence and self-assertiveness.</p>
                    <a class="start-icon">Start now <i class="fa fa-long-arrow-right" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
      </div>
 </div>
</section>
<!--Sezione img + tab-->
<SectionWithTab></SectionWithTab>
<!--Barra numeri da aggiunger con il v-for-->
<div class="bg-color" style="height:80px">
   <div class="d-flex align-center">
    INSERIRE CON IL V FOR 
   </div>
</div>
<!--Sezione Lastest Featured-->
 <section class="container space-top-bottom">
     <div class="text-center">
        <h4>CHOOSE WHERE YOU'D LIKE TO BEGIN</h4>
        <h1 class="">Lastest Featured <span class="word-green">Courses</span></h1>
     </div>
<CardCourses></CardCourses>
</section>
</div>
</template>

<script>
import CardCourses from "./CardCourses.vue"
import SectionWithTab from "./SectionWithTab.vue"

export default {
  name: "MainBlock1",
  components: {
    SectionWithTab,
    CardCourses,
  },
};

</script>

<style lang="scss">
/*.card-header{
    background-color: chocolate!important;
}*/
.card-img-top {
    width: 100%;
    height: 150px;
    object-fit: contain;
    }
.start-icon{
    text-decoration: none;
    color: grey;
    font-weight: bold;
}
</style>
