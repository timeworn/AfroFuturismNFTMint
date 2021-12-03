<template>
  <footer class="py-sm text-white">
    <div class="container mt-5">
      <div class="row px-2 mt-3">
        <div class="col-md-4 col-xl-3 mx-auto mb-md-2 mb-3">
          <h1 class="text-uppercase h1 font-weight-semi-bold">Logo Here</h1>
          <div class="pt-2">
            <i class="footer-icons fa fa-twitter mr-1"></i>
            <i class="footer-icons fa fa-reddit-alien"></i>
          </div>
        </div>
        <div class="col-md-4 mx-auto mb-md-2 mb-3">
          <h3 class="font-weight-semi-bold">Navigation</h3>
          <ul class="pt-2 row text-sm">
            <li class="pb-1 col-6">
              <a class="text-white" href="/">Home</a>
            </li>
            <li class="pb-1 col-6">
              <a class="text-white" href="/">Roadmap</a>
            </li>
            <li class="pb-1 col-6">
              <a class="text-white" href="/">Mint</a>
            </li>
            <li class="pb-1 col-6">
              <a class="text-white" href="/">Team</a>
            </li>
            <li class="pb-1 col-6">
              <a class="text-white" href="/">Mission</a>
            </li>
            <li class="pb-1 col-6">
              <a class="text-white" href="/">FAQ</a>
            </li>
            <li class="pb-1 col-7">
              <a class="text-white" href="/">Member Perks</a>
            </li>
          </ul>
        </div>
        <div class="col-md-3 mx-auto mb-md-0 mb-3">
          <h3 class="font-weight-semi-bold">Get Latest Updates</h3>
          <input
            type="email"
            name="email"
            placeholder="Your Email Address..."
            class="input rounded-pill px-2 py-sm mt-2 w-100 text-white"
          />
          <button class="text-white text-sm rounded-pill mt-1 h6">
            Subscribe
          </button>
        </div>
      </div>
    </div>
    <div class="footer-copyright py-sm text-center text-white text-sm">
      &copy; Copyright 2021 NAME HERE | All Right Reserved
    </div>
  </footer>
</template>

<style scoped>
footer {
  background: #151414;
}
.footer-copyright {
  background: #131212;
}
.footer-icons {
  font-size: 30px;
}
h1.h1 {
  font-size: 34px;
  line-height: 30px;
}
.input {
  background: #1f1e1e;
  border: none;
}
.input:focus {
  outline: none;
}
button {
  background-image: linear-gradient(#7355b0, #6975dd);
  padding: 1.1rem 3.5rem !important;
  border: none;
  box-shadow: 0px 0px 10px -1px #6975dd;
}
button:focus {
  outline: none;
}
</style>
