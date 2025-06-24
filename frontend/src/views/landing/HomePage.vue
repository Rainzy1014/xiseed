<template>
  <div id="home-page">
    <Header />
    <!-- Carousel -->
    <div id="home-carousel" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#home-carousel" data-slide-to="0" class="active"></li>
        <li data-target="#home-carousel" data-slide-to="1"></li>
      </ol>
      <div class="carousel-inner" role="listbox">
        <div class="item active">
          <img src="../../assets/landing/img/banner_1.jpg" alt="Banner 1" />
        </div>
        <div class="item">
          <img src="../../assets/landing/img/banner_2.jpg" alt="Banner 2" />
        </div>
      </div>
      <a class="left carousel-control" href="#home-carousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#home-carousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    <!-- Simple Content Section -->
    <div class="container text-center" style="padding: 40px 0;">
      <h2>欢迎来到我们的网站</h2>
      <p class="lead">这是一个基于旧模板整合的现代化网站首页。</p>
    </div>
    <Footer />
    <GoTop />
  </div>
</template>

<script setup>
import Header from './Header.vue';
import Footer from './Footer.vue';
import GoTop from './GoTop.vue';
</script>

<style scoped>
/* Importing Bootstrap CSS locally from assets */
@import '../../assets/landing/css/bootstrap.min.css';
@import '../../assets/landing/css/reset.min.css';

#home-page {
  width: 100%;
}
.carousel-inner .item img {
  width: 100%;
}
</style>

