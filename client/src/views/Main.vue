@@ -1,85 +1,32 @@
<template>
  <div>
    <AfroFuturism />
  </div>
</template>

<script>
import AfroFuturism from "@/components/afFuturism.vue";

export default {
  name: "App",
  components: {
    AfroFuturism,
  },
};
</script>

<style>
.sec-main-top {
  background: #01100f;
  background-image: url("../assets/img/topback.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.about-sec-ma {
  background: #01100f;
  padding: 4rem 0rem 14rem;
}

.sample-women-sec {
  background: #01100f;
  padding: 4rem 0rem 14rem;
}

.symbol-women-sec {
  padding-top: 50px;
  padding-bottom: 250px;
  background: #01100f;
  background-image: url("../assets/img/secondback_1.png");
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: bottom;
}

.road-map-se {
  margin-top: 0px;
  background: #01100f;
  background-image: url("../assets/img/secondback_2.png");
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: top;
  padding-bottom: 90px;
}

.road-map-se-content {
  position: absolute;
  bottom: 0;
  left: 41%;
}

.road-2nd-mapp-sc {
  background: #01100f;
  position: relative;
  background-image: url("../assets/img/roadmap-bg.png");
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: bottom;
  padding-bottom: 100px;
}

.our-team-sec-main {
  position: relative;
  padding-bottom: 10rem;
  background-image: url("../assets/img/about-bg.png");
  background-repeat: no-repeat;
  background-color: #01100f;
  background-position-x: center;
  background-position-y: top;
  margin-top: 0px;
}
.team-sec-main {
  position: relative;
  padding-bottom: 10rem;
  background-image: url("../assets/img/_Image_.png");
  background-repeat: no-repeat;
  background-color: #01100f;
  background-position-x: center;
  background-position-y: top;
  margin-top: 0px;
}
</style>
