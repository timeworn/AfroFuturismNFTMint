<template>
  <fixed-header>
    <div class="navbar">
      <nav
        class="
          navbar navbar-expand-md
          align-items-center
          text-white
          navbar-dark
          pt-2
          px-2 px-md-0 px-lg-2
          container
        "
      >
        <a class="navbar-brand text-white" href="/home">
          <h2 class="text-uppercase h1 font-weight-semi-bold">Logo Here</h2></a
        >
        <button
          class="navbar-toggler text-white"
          type="button"
          @click="collapes = !collapes"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapses navbar-collapse d-none">
          <div
            class="
              d-flex
              flex-column
              align-items-md-end align-items-center
              justify-content-md-end
              w-100
            "
          >
            <div class="d-flex align-items-center mt-2 mt-sm-0">
              <i class="icons fa fa-twitter mr-1"></i>
              <i class="icons fa fa-reddit-alien mr-2"></i>
              <button class="text-white btn-primary" type="submit">
                Connect Wallet
              </button>
            </div>
            <ul
              class="navbar-nav align-items-md-center ml-lg-auto mt-1 text-sm"
            >
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#">Home</a>
              </li>
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#mint">Mint</a>
              </li>
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#mission">Mission</a>
              </li>
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#member">Member Perks</a>
              </li>
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#roadmap">Roadmap</a>
              </li>
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#team">Team</a>
              </li>
              <li class="nav-item my-1 my-sm-0">
                <a class="nav-link text-whites" href="#faq">FAQ</a>
              </li>
            </ul>
          </div>
        </div>
        <transition name="fade">
          <div class="w-100 d-md-none" v-if="collapes === true">
            <div
              class="
                d-flex
                flex-column
                align-items-md-end align-items-center
                justify-content-md-end
                w-100
                py-2 py-md-0
              "
            >
              <div class="d-flex align-items-center mt-2 mt-sm-0">
                <i class="icons fa fa-twitter mr-1"></i>
                <i class="icons fa fa-reddit-alien mr-2"></i>
                <button class="text-white btn-primary" type="submit">
                  Connect Wallet
                </button>
              </div>
              <ul
                class="navbar-nav align-itemss-center ml-lg-auto mt-1 text-sm"
              >
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#">Home</a>
                </li>
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#mint">Mint</a>
                </li>
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#mission">Mission</a>
                </li>
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#member"
                    >Member Perks</a
                  >
                </li>
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#roadmap">Roadmap</a>
                </li>
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#team">Team</a>
                </li>
                <li class="nav-item my-1 my-sm-0">
                  <a class="nav-link text-whites" href="#faq">FAQ</a>
                </li>
              </ul>
            </div>
          </div>
        </transition>
      </nav>
    </div>
  </fixed-header>
</template>

<script>
import FixedHeader from "vue-fixed-header";

export default {
  components: {
    FixedHeader,
  },
  data() {
    return {
      collapes: false,
    };
  },
};
</script>

<style>
.btn-primary {
  border-radius: 25px !important;
  background-image: linear-gradient(#7355b0, #6975dd);
  border: none;
  font-weight: lighter;
  padding: 1rem 2.5rem !important;
  font-size: 1.2rem !important;
  box-shadow: 0px 0px 10px -1px #6975dd;
}
.icons {
  font-size: 25px;
}
.nav-link {
  color: #ffffff !important;
  text-align: center;
  border-radius: 50px;
  padding: 7px 20px;
  max-width: 100px;
  min-width: 85px;
  transition: all 0.5s;
}
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link:hover,
.navbar-dark .navbar-nav .nav-link:focus {
  background-image: linear-gradient(#7355b0, #6975dd);
  box-shadow: 0px 0px 6px -1px #6975dd;
}
.navbar.vue-fixed-header--isFixed {
  position: fixed;
  left: 0;
  top: 0;
  background: #131212;
  width: 100vw;
  transition: all 1s;
  z-index: 1000;
  box-shadow: 0 0 5px 1px rgba(255, 255, 255, 0.2);
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>
