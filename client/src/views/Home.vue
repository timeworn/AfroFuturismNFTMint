<template>
  <div class="home">
    <Header />
    <Timer />
    <div class="pt-5 pb-4">
      <section id="mission">
        <div class="col-md-12 d-flex flex-column align-items-center pt-100">
          <img
            src="../assets/img/Mission.png"
            width="270px"
            class="mb-30"
            alt=""
          />
          <p class="para text-center text-white col-sm-9 mb-50">
            Nam vulputate metus at arcu fermentum auctor. Nunc porttitor justo
            non tellus eleifend auctor. Aliquam ac felis a nunc imperdiet
            porttitor ac sit amet sem. Cras id dapibus ipsum, in ullamcorper
            enim. Nulla nisl libero, suscipit eu sagittis quis, dictum at neque.
            Proin dignissim sit amet nulla a ornare. Aenean rutrum volutpat
            fermentum. Nulla feugiat aliquet tincidunt. Sed at luctus velit,
            eget imperdiet lacus. Maecenas at porta tellus. Cras sit amet turpis
            a metus luctus viverra quis at odio.
          </p>
        </div>
      </section>
      <section id="member">
        <div class="col-md-12 d-flex flex-column align-items-center pt-100">
          <img
            src="../assets/img/member.png"
            width="300px"
            class="mb-30"
            alt=""
          />
          <p class="para text-center text-white col-sm-9 mb-50">
            Integer feugiat et nisl et mollis. Integer scelerisque, tellus vel
            pharetra sollicitudin, metus massa fringilla libero, nec interdum
            elit felis sed purus. Nam quis feugiat risus. Donec maximus
            ultricies lectus, sed cursus nibh convallis nec. Nullam augue enim,
            sagittis sit amet tellus vel, vulputate vulputate lacus. Curabitur
            feugiat, magna vel interdum efficitur, justo libero sollicitudin
            metus, sed lobortis ligula ipsum vitae ipsum. Mauris aliquet elit eu
            condimentum placerat. Sed et elit elit. In feugiat elementum
            sagittis.
            <br />
            <br />
            Morbi tempor volutpat condimentum. Nunc commodo nisi eu odio
            venenatis, nec rhoncus arcu auctor. Donec sit amet nisl sit amet
            neque dignissim luctus. Sed pulvinar nisi quis urna vulputate
            accumsan. Nam malesuada et felis sed rhoncus. Donec eget iaculis
            urna.
          </p>
        </div>
      </section>

      <Roadmap />
      <Team />
      <FAQ />
    </div>
    <Footer />
  </div>
</template>
<script>
import Header from "@/components/Header/index.vue";
import Timer from "@/components/timer.vue";
import Roadmap from "@/components/roadmapNew.vue";
import Team from "@/components/team.vue";
import FAQ from "@/components/faq.vue";
import Footer from "@/components/Footer/index.vue";
export default {
  components: {
    Header,
    Timer,
    Roadmap,
    Team,
    FAQ,
    Footer,
  },
};
</script>
<style>
.home {
  background-image: url("../assets/img/main.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
</style>
