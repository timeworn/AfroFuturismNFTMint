<template>
  <section id="faq">
    <div class="d-flex justify-content-center pt-100 mt-70">
      <img src="../assets/img/FAQ.png" width="140px" class="mb-30" alt="" />
    </div>
    <div class="d-flex justify-content-center px-2">
      <VueFaqAccordion :items="myItems" />
    </div>
  </section>
</template>

<script>
import VueFaqAccordion from "vue-faq-accordion";

export default {
  components: {
    VueFaqAccordion,
  },
  data() {
    return {
      myItems: [
        {
          title: "1: How is it going work?",
          value:
            "Nulla lacinia pellentesque erat ac sollicitudin. Mauris in turpis nec sapien placerat bibendum. Integer nec mi vel metus tincidunt porta ut id eros. Curabitur laoreet est in metus lacinia auctor quis eget mauris. Nulla facilisi. Vivamus pharetra dignissim neque, id dignissim est consequat ut.  Aenean molestie dapibus lacus, in tincidunt turpis efficitur at. Nunc laoreet pellentesque justo nec molestie. Nam nec malesuada ex.",
        },
        {
          title: "2: How does the this do and what?",
          value:
            "Nulla lacinia pellentesque erat ac sollicitudin. Mauris in turpis nec sapien placerat bibendum. Integer nec mi vel metus tincidunt porta ut id eros. Curabitur laoreet est in metus lacinia auctor quis eget mauris. Nulla facilisi. Vivamus pharetra dignissim neque, id dignissim est consequat ut.  Aenean molestie dapibus lacus, in tincidunt turpis efficitur at. Nunc laoreet pellentesque justo nec molestie. Nam nec malesuada ex.",
        },
        {
          title: "3: How is it going work?",
          value:
            "Nulla lacinia pellentesque erat ac sollicitudin. Mauris in turpis nec sapien placerat bibendum. Integer nec mi vel metus tincidunt porta ut id eros. Curabitur laoreet est in metus lacinia auctor quis eget mauris. Nulla facilisi. Vivamus pharetra dignissim neque, id dignissim est consequat ut.  Aenean molestie dapibus lacus, in tincidunt turpis efficitur at. Nunc laoreet pellentesque justo nec molestie. Nam nec malesuada ex.",
        },
        {
          title: "4: How does the this do and what?",
          value:
            "Nulla lacinia pellentesque erat ac sollicitudin. Mauris in turpis nec sapien placerat bibendum. Integer nec mi vel metus tincidunt porta ut id eros. Curabitur laoreet est in metus lacinia auctor quis eget mauris. Nulla facilisi. Vivamus pharetra dignissim neque, id dignissim est consequat ut.  Aenean molestie dapibus lacus, in tincidunt turpis efficitur at. Nunc laoreet pellentesque justo nec molestie. Nam nec malesuada ex.",
        },
      ],
    };
  },
};
</script>

<style>
.faq-wrapper[data-v-5d9392b3] {
  max-width: 800px !important;
  margin: auto;
}
.accordion__title[data-v-5d9392b3] {
  padding: 18px 25px 18px 45px !important;
  color: white !important;
  font-size: 15px;
  font-weight: 500;
  border-radius: 50px;
  margin-bottom: 25px;
  border: 2px solid white;
}
.accordion__title_active[data-v-5d9392b3] {
  background-image: linear-gradient(#7355b0, #6975dd);
  box-shadow: 0px 0px 15px -2px #6975dd;
  border: none;
}
.accordion[data-v-5d9392b3] {
  border: none !important;
  border-radius: 0px !important;
  margin-top: 15px;
}
.accordion__item {
  border-bottom: none !important;
}
.accordion__toggle-button[data-v-5d9392b3]::before,
.accordion__toggle-button[data-v-5d9392b3]::after {
  background: white !important;
}
.accordion__value[data-v-5d9392b3] {
  padding: 0 20px 25px 57px !important;
  color: white !important;
  font-size: 11px !important;
  line-height: 19px;
}
.accordion__toggle-button_active[data-v-5d9392b3],
.accordion__toggle-button[data-v-5d9392b3]::before {
  transform: rotate(0deg) !important;
  height: 4px !important;
}
</style>
