<template>
    <section class="sample-women-sec">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="tittle-sample">
              Sample Women
            </div>
          </div>
        </div>
        <div class="slider-sample">
          <VueSlickCarousel v-bind="settings" :arrows="true" :dots="true">
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-1.jpg" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-2.png" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-3.png" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-1.jpg" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-2.png" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-3.png" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-1.jpg" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-2.png" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-3.png" class="img-fluid">
                </div>
              </div>
            </div>
            <div class="">
              <div class="main-image-wraper-sam">
                <div class="inner-image-wrap d-flex align-items-center">
                  <img src="../assets/img/samp-1.jpg" class="img-fluid">
                </div>
              </div>
            </div>
          </VueSlickCarousel>
        </div>
      </div>
    </section>
</template>

<script>
    import VueSlickCarousel from 'vue-slick-carousel';

    import 'vue-slick-carousel/dist/vue-slick-carousel.css';
    import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css';

    export default {
      name: "sample",
      components: {VueSlickCarousel},

      data() {
      return {
        settings: {
          "focusOnSelect": true,
          "infinite": true,
          "speed": 500,
          "slidesToShow": 4,
          "slidesToScroll": 1,
          "initialSlide": 0,
          "responsive": [
            {
              "breakpoint": 1024,
              "settings": {
                "slidesToShow": 3,
                "slidesToScroll": 3,
                "infinite": true,
                "dots": true
              }
            },
            {
              "breakpoint": 600,
              "settings": {
                "slidesToShow": 2,
                "slidesToScroll": 2,
                "initialSlide": 2
              }
            },
            {
              "breakpoint": 480,
              "settings": {
                "slidesToShow": 1,
                "slidesToScroll": 1
              }
            }
          ]
        }
      }
    },

    mounted() {
    },
    computed: {
    }
  }
</script>

<style>

  @import "https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/css/select2.min.css";

  @import "../assets/css/main.css";

  @import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.css";

  @import "https://fonts.googleapis.com";

  @import "https://fonts.gstatic.com";

  @import "https://cdn.jsdelivr.net/npm/select2@4.1.0-rc.0/dist/css/select2.min.css";

  @import "https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap";

  @import "https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css";

  @import "../assets/slick/slick.css";

  @import "../assets/slick/slick-theme.css";

button.slick-prev:before, button.slick-next:before {
      font-size: 22px;
      margin:0 1px;
}

</style>