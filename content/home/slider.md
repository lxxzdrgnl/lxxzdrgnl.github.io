---
widget: blank
headless: true
weight: 0
design:
  container: 'fullwidth'
---

<h2 style="text-align: center;">좋아하는 앨범</h2>

<!-- Link Swiper's CSS -->
<link
  rel="stylesheet"
  href="https://unpkg.com/swiper/swiper-bundle.min.css"
/>

<style>
.swiper-container {
  width: 100%;
  height: 55vh;
}
.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;

  /* Center slide text vertically */
  display: -webkit-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  -webkit-align-items: center;
  align-items: center;
}
</style>

<!-- Swiper -->
<div class="swiper-container">
  <div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide" style="background-image:url('/ilmatic.png'); background-size: cover; background-position: center;"></div>
    <div class="swiper-slide" style="background-image:url('/이방인.png'); background-size: cover; background-position: center;"></div>
    <div class="swiper-slide" style="background-image:url('/damn.png'); background-size: cover; background-position: center;"></div>
    <div class="swiper-slide" style="background-image:url('/에넥도트.png'); background-size: cover; background-position: center;"></div>
    <div class="swiper-slide" style="background-image:url('/디카프리오.jpg'); background-size: cover; background-position: center;"></div>
    <div class="swiper-slide" style="background-image:url('/tpab.jpg'); background-size: cover; background-position: center;"></div>
  </div>
  <!-- Add Pagination -->
  <div class="swiper-pagination"></div>
  <!-- Add Navigation -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
</div>

<!-- Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

<!-- Initialize Swiper -->
<script>
  var swiper = new Swiper('.swiper-container', {
    observer: true,
    observeParents: true,
    loop: true,
    initialSlide: 1, // Start on the second slide
    slidesPerView: 1.1,
    spaceBetween: 10,
    centeredSlides: false,
    pagination: {
      el: '.swiper-pagination',
      clickable: true,
    },
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
    autoplay: {
      delay: 1000,
    },
  });
</script>
