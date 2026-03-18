---
layout: archive
title: "Photography"
permalink: /photography/
author_profile: true
---

Here are some of my favorite photographs, all taken by me.

---

## Landscapes
<div class="swiper mySwiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="/images/photography/DSC_0668.jpg" alt="Glacier National Park" loading="lazy">
      <div class="cap">Glacier National Park</div>
    </div>
    <div class="swiper-slide">
      <img src="/images/photography/DSC_5425-2.jpg" alt="Arches National Park" loading="lazy">
      <div class="cap">Arches National Park</div>
    </div>
    <div class="swiper-slide">
      <img src="/images/photography/canyonlands_island_sky.jpg" alt="Canyonlands National Park" loading="lazy">
      <div class="cap">Canyonlands National Park</div>
    </div>
  </div>

  <!-- Navigation controls -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
  <div class="swiper-pagination"></div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const swiper = new Swiper('.mySwiper', {
      loop: true,
      spaceBetween: 20,
      centeredSlides: true,
      slidesPerView: 1,
      keyboard: { enabled: true },
      navigation: {
        nextEl: '.mySwiper .swiper-button-next',
        prevEl: '.mySwiper .swiper-button-prev',
      },
      pagination: {
        el: '.mySwiper .swiper-pagination',
        clickable: true,
      },
      lazy: true,
      breakpoints: {
        768: { slidesPerView: 1.05 },
      }
    });
  });
</script>
