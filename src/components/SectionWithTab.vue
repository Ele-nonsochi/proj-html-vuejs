<template>
 <div>
  <section class="row padding-lr space-top-bottom">
    <div class="col-6 container-career position-relative">
      <img class="about-us-img" src="@/assets/images/about-us-03-image-01.png" alt="image">
      <img src="@/assets/images/underlay-shape-lilla.svg" alt="image" class="bg-img">
    </div>
    <div class="col-6 content-position">
       <h4>DREAM WITH <strong>MAXCOACH</strong></h4>
       <h1 class="pb-3">Construct A <span class="word-green">stunning</span> Career Perspective</h1>
        <div class="card bg-card">
    <div class="card-header-special" id="headingOne">
      <h5 class="mb-0">Multiple Platform Supported for Teaching & Studying
      <a class="d-inline"><i class="fa fa-minus-circle" aria-hidden="true"></i></a>
      </h5>
    </div>
    <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordion">
      <div class="card-body">
        MaxCoach supports the act of teaching and learning on multiple platforms like online or offline via material downloads. We know things aren't supposed to be devoured in a short time, you can always access our knowledge base from any device.
      </div>
    </div>
  </div>
  <div class="card bg-card">
    <div class="card-header" id="headingTwo">
      <h5 class="mb-0">
          Multiple Course Partecipation at the Same Time
        <a class="d-inline"><i class="fa fa-plus-circle"></i></a>
      </h5>
    </div>
    </div>
    <div class="card bg-card">
    <div class="card-header" id="headingTwo">
      <h5 class="mb-0">
          Track Study Progress & Deliver Prompt Feedback
        <a class="d-inline"><i class="fa fa-plus-circle"></i></a>
      </h5>
    </div>
    </div>
    </div>
</section>
 </div>
</template>

<script>

export default {
  name: "SectionWithTab",
  components: {
   
  },
};
</script>

<style lang="scss">
.card-header-special{
    background-color: #62c5b5;
    padding-top: 10px;
    padding-bottom: 10px;
    font-size: 8px;
    color: white;
    .fa{
        color: white;
        padding-left: 15px;
    }
}
.about-us-img{
   position: relative;
   top: 0;
   left: 0;
   z-index: 99;
}
.bg-img{
    position:absolute;
    position: absolute;
    top: 0;
    width: 70%;
    right: 90px;
    }
</style>
