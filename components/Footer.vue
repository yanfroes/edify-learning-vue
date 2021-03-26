<template>
    <div>
      <footer class="site-footer">
                  <div class="site-footer__bottom">
                      <div class="container">
                          <p class="site-footer__copy">&copy; Copyright 2020 by <a href="#">EdifyOnline.com</a></p>
                          <div class="site-footer__social">
                              <a href="#" data-target="html" class="scroll-to-target site-footer__scroll-top"><i class="kipso-icon-top-arrow"></i></a>
                              <a href="#"><i class="fab fa-twitter"></i></a>
                              <a href="#"><i class="fab fa-facebook-square"></i></a>
                              <a href="#"><i class="fab fa-linkedin"></i></a>
                              <a href="#"><i class="fab fa-instagram"></i></a>
                          </div><!-- /.site-footer__social -->
                          <!-- /.site-footer__copy -->
                      </div><!-- /.container -->
                  </div><!-- /.site-footer__bottom -->
              </footer>
      <div class="search-popup">
              <div class="search-popup__overlay custom-cursor__overlay">
                  <div class="cursor"></div>
                  <div class="cursor-follower"></div>
              </div><!-- /.search-popup__overlay -->
              <div class="search-popup__inner">
                  <form action="#" class="search-popup__form">
                      <input type="text" name="search" placeholder="Type here to Search....">
                      <button type="submit"><i class="kipso-icon-magnifying-glass"></i></button>
                  </form>
              </div><!-- /.search-popup__inner -->
          </div>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>

</style>
