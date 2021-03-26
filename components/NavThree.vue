<template>
  <header class="site-header site-header__home-three ">
      <div class="topbar-one">
          <div class="container">
              <div class="topbar-one__left">

              </div><!-- /.topbar-one__left -->
              <div class="topbar-one__right">
                  <a href="https://www.edifyonline.com/login">Login</a>
                  <a href="https://www.edifyonline.com/signup">Register</a>
              </div><!-- /.topbar-one__right -->
          </div><!-- /.container -->
      </div><!-- /.topbar-one -->
      <nav class="navbar navbar-expand-lg navbar-light header-navigation stricky">
          <div class="container clearfix">
              <!-- Brand and toggle get grouped for better mobile display -->
              <div class="logo-box clearfix">
                  <a class="navbar-brand" href="/">
                      <img src="/assets/images/logo-light.png" class="main-logo" width="110" alt="Awesome Image" />
                  </a>
                  <button class="menu-toggler" data-target=".main-navigation">
                      <span class="kipso-icon-menu"></span>
                  </button>
              </div><!-- /.logo-box -->
              <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="main-navigation">
                                          <ul class=" navigation-box">
                                              <li class="current">
                                                  <a href="/">Home</a>
                                              </li>
                                              <li>
                                                  <nuxt-link to="/course-details">About Us</nuxt-link>
                                              </li>
                                              <li>
                                                  <nuxt-link to="/our-mission">Our Mission</nuxt-link>
                                              </li>
                                              <li>
                                                  <nuxt-link to="/teachers">Our People</nuxt-link>
                                              </li>
                                              <li>
                                                  <nuxt-link to="/contact">Contact</nuxt-link>
                                              </li>
                                          </ul>
                                      </div><!-- /.navbar-collapse -->
              <div class="right-side-box">
                  <div class="header__social">
                      <a href="#"><i class="fab fa-twitter"></i></a>
                      <a href="#"><i class="fab fa-facebook-square"></i></a>
                      <a href="#"><i class="fab fa-linkedin"></i></a>
                      <a href="#"><i class="fab fa-instagram"></i></a>
                  </div><!-- /.header__social -->
              </div><!-- /.right-side-box -->
          </div>
          <!-- /.container -->
      </nav>
  </header>
</template>

<script>
    export default {
        name: "NavThree"
    }
</script>

<style scoped>

</style>
