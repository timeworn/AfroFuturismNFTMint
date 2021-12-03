<template>
  <section id="mint">
    <div class="container pt-100 pb-5">
      <h1 class="pt-5 text-white text-center">Minting Begins Friday</h1>
      <div class="row justify-content-center pt-5">
        <div
          class="
            border
            rounded-xl
            counter
            py-md-3 py-2
            px-md-3 px-1
            text-white text-center
            mx-1
            mb-1
          "
          style="width: 120px"
          v-for="v in timer"
          :key="v"
        >
          <span class="h1 pb-1 font-weight-normal" style="font-size: 38px">{{
            v.time
          }}</span>
          <p class="mb-0 text-sm font-weight-normal">{{ v.title }}</p>
        </div>
      </div>
      <div class="box-counter py-5 px-4 mb-5">
        <p class="h1 pb-2 font-weight-lighter text-white">
          Mint Price: 010 ETH
        </p>
        <div class="number">
          <span class="minus" @click="sub">-</span>
          <div>
            <input v-model="count" />
            <h6 class="text-white text-center font-weight-normal text-sm">
              {{ count }} Mint
            </h6>
          </div>
          <span class="plus" @click="add">+</span>
        </div>
        <button type="button" class="btn text-uppercase border btn-custom">
          mint
        </button>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      count: 0,
      timer: [
        { time: "01", title: "Days" },
        { time: "08", title: "Hours" },
        { time: "54", title: "Minutes" },
        { time: "58", title: "Seconds" },
      ],
    };
  },
  methods: {
    emitResult() {
      this.$emit("input", this.count);
    },
    add() {
      this.count += 1;
      this.emitResult();
    },
    sub() {
      this.count -= 1;
      this.emitResult();
    },
  },
  // methods: {
  //   add() {
  //     this.counter += 1;
  //   },
  //   sub() {
  //     this.counter -= 1;
  //   },
  // },
};
</script>

<style scoped>
.box-counter {
  background: #000303;
  margin-top: 40px !important;
  max-width: 380px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  margin: 0 auto;
  box-shadow: inset 0px 0px 4px 6px #202323;
  border-radius: 14px;
}
.btn-custom {
}
.number input {
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  font-size: 24px;
  font-weight: 200;
  margin: 3px auto;
}
@media (max-width: 767px) {
  .counter {
    width: 70px !important;
  }
  .counter .h1 {
    font-size: 24px !important;
  }
}
</style>
