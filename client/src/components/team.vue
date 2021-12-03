<template>
  <section id="team">
    <div class="container pt-5">
      <div class="row">
        <div class="col-md-12 d-flex flex-column align-items-center">
          <img
            src="../assets/img/Team.png"
            width="140px"
            class="mb-30"
            alt=""
          />
          <p class="para text-center text-white col-sm-9 mb-50">
            Morbi quis risus at mauris volutpat sodales. Suspendisse ultrices
            eros in augue finibus, sed convallis felis ullamcorper. Cras sodales
            purus ac cursus fermentum. Ut non tempus odio. Nulla consequat
            gravida dolor ut accumsan. Suspendisse ullamcorper purus mattis
            suscipit cursus. Proin porta libero nec nulla scelerisque tempor
            eget rutrum tortor. Nam venenatis lectus non ipsum ultricies
            finibus. Nunc rutrum, justo non iaculis blandit, felis mi lobortis
            velit, eu aliquet felis lacus quis nisi.
          </p>
        </div>
        <div class="row col-sm-11 col-md-12 col-lg-11 col-xl-10 mx-auto">
          <div
            class="
              col-lg-3 col-md-3 col-6
              d-flex
              flex-column
              align-items-center
              mx-auto
              px-lg-2 px-1
              py-2
            "
            v-for="n in 4"
            :key="n"
          >
            <div class="main-wraper-team px-1 py-2">
              <img
                src="../assets/img/team-2.png"
                height="200px"
                class="rounded-xl mx-auto w-100"
              />
              <div class="pt-2">
                <h2 class="text-center text-white">Raphael Malavieille</h2>
                <p class="text-sm mb-0 text-white text-center">Lead Artist</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Team",
  data() {
    return {};
  },
  mounted() {},
  computed: {},
};
</script>

<style></style>
