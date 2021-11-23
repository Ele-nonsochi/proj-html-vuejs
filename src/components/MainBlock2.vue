<template>
<!--Secondo blocco Main inizio Learn at Your..-->
<div>
<section class="container pb-5">
   <div class="row align-items-center">
        <div class="col-6">
               <div class="">
               <h3>WHY HESITATE TO REGISTER?</h3>
               <h1>Learn At Your Own Pace</h1>
               <ul>
                   <li>Select & costumize courses to your preferences</li>
                   <li>Change the tutor and make arrangements</li>
                   <li>Participate in events to join others</li>
                   <li>Get the desired certificate delivered at house</li>
               </ul>
               <a href="#" class="button-page">Get started for free</a>
               </div>
         </div>
         <div  class="col-6">
            <div class="card">
                <img src="@/assets/images/home-5-image-01.png" alt="image">
            </div>
         </div>
        </div>
</section>
<section class="container pb-5">
    <div class="row align-items-center" >
    <div  class="col-6">
        <div class="card">
            <img src="@/assets/images/home-5-image-02.png" alt="image">
        </div>
         </div>
         <div class="col-6">
               <div class="">
               <h3>WHAT ARE YOU LOOKING FOR?</h3>
               <h1>Learn on your mobile anytime!</h1>
               <p>Save lessons for later and revise or write notes at any time and on multiple devices on your way.Never interfere with activities of enjoyment or other precious moments.</p>
               <a href="#" class="button-page">Download Our App</a>
               </div>
         </div>  

        </div>
</section>
<!--Event Card-->
<section>
    <div class="container">
    <div class="text-center">
        <h4>GET IN CONTACT NOW</h4>
        <h1 class="">Upcoming Events</h1>
        <EventCard></EventCard>
     </div>
    </div>
</section>
</div>
</template>

<script>
import EventCard from "./EventCard.vue"

export default {
  name: "MainBlock2",
  components: {
      EventCard,
  },
};
</script>

<style lang="scss">

</style>