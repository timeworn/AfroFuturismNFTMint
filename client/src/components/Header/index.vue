<template>
  <div class="bg-main">
    <Navbar />
    <div class="container text-center text-white py-5">
      <h1 class="font-weight-bold">Meta Women DAO</h1>
      <p
        class="
          para
          col-lg-7 col-md-10 col-12
          mx-auto
          font-weight-lighter
          pb-5
          px-0 px-md-3
        "
      >
        Praesent a metus ac orci dictum dapibus. Quisque feugiat nibh vel luctus
        euismod. Nunc vitae elit auctor, dapibus nisi non, lobortis dui. Donec
        varius felis et odio scelerisque, ut luctus diam ullamcorper. Praesent
        ac tristique diam.
      </p>
      <div class="row justify-content-center pb-2 px-1">
        <img class="border col px-0" src="../../assets/img/img-1.png" alt="" />
        <img class="border col px-0" src="../../assets/img/img-3.png" alt="" />
        <img class="border col px-0" src="../../assets/img/img-4.png" alt="" />
        <img class="border col px-0" src="../../assets/img/img-2.png" alt="" />
        <img class="border col px-0" src="../../assets/img/img-3.png" alt="" />
      </div>
    </div>
  </div>
</template>
<script>
import Navbar from "@/components/navbar.vue";
export default {
  components: {
    Navbar,
  },
};
</script>
<style scoped>
.bg-main {
  background-image: url("../../assets/img/bg-header.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
.bg-main h1 {
  font-size: 50px;
  font-family: serif;
}
@media (max-width: 540px) {
  .bg-main h1 {
    font-size: 35px;
  }
}
</style>
