<template>
  <div id="app">

  <header class="header">
    <nav class="navbar navbar-expand-lg fixed-top">
      <div class="container"><a href="#intro" class="navbar-brand scrollTo">Kyle Hassett</a>
        <button type="button" data-toggle="collapse" data-target="#navbarcollapse" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler navbar-toggler-right"><span class="fa fa-bars"></span></button>
        <div id="navbarcollapse" class="collapse navbar-collapse">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a href="#intro" class="nav-link link-scroll">Intro</a></li>
            <li class="nav-item"><a href="#about" class="nav-link link-scroll">About</a></li>
            <li class="nav-item"><a href="#services" class="nav-link link-scroll">Services</a></li>
            <li class="nav-item"><a href="#testimonials" class="nav-link link-scroll">Testimonials</a></li>
            <li class="nav-item"><a href="#references" class="nav-link link-scroll">My work</a></li>
            <li class="nav-item"><a href="#customers" class="nav-link link-scroll">Clients</a></li>
            <li class="nav-item"><a href="#contact" class="nav-link link-scroll">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </header>


  <router-view/>

  <footer class="main-footer">
    <div class="container">
      <div class="row">
        <div class="col-md-6 text-center text-lg-left">
          <p class="social"><a href="https://github.com/kyle-hassett" target="_blank" data-wow-delay="0.2s" class="external github wow fadeInUp"><i class="fa fa-github"></i></a><a href="https://www.linkedin.com/in/kyle-hassett-/" target="_blank" data-wow-delay="0.2s" class="external linkedin wow fadeInUp"><i class="fa fa-linkedin"></i></a></p>
        </div>
        <!-- /.6-->
        <div class="col-md-6 text-center text-lg-right mt-4 mt-lg-0">
          <p>© 2018 Kyle Hassett. All rights reserved.</p>
        </div>
        <div class="col-12 mt-4">
          <p class="template-bootstrapious">Designed by <a href="https://www.bootstrapious.com">Bootstrapious</a>
            <!-- Please do not remove the backlink to us unless you support further theme's development at https://bootstrapious.com/donate. It is part of the license conditions. Thank you for understanding :)-->
          </p>
        </div>
      </div>
    </div>
  </footer>

  </div>
</template>

<style>
.selfie {
  border-radius: 50%;
}
</style>
