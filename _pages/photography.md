---
layout: archive
title: "Photography"
permalink: /photography/
author_profile: true
---

A few of my favorite photographs, all taken by me.

## Landscapes

<div class="photo-rows">
  <div class="photo-row">
    <figure class="photo" style="--ratio: 1.803">
      <button class="photo__frame" type="button" data-full="/images/photography/canyonlands_island_sky.jpg" data-caption="Canyonlands National Park · Utah">
        <img src="/images/photography/canyonlands_island_sky.jpg" alt="Canyonlands National Park, Utah" loading="lazy">
      </button>
      <figcaption><span class="photo__title">Canyonlands National Park</span><span class="photo__place">Utah</span></figcaption>
    </figure>
  </div>
  <div class="photo-row">
    <figure class="photo" style="--ratio: 1.503">
      <button class="photo__frame" type="button" data-full="/images/photography/DSC_0668.jpg" data-caption="Glacier National Park · Montana">
        <img src="/images/photography/DSC_0668.jpg" alt="Glacier National Park, Montana" loading="lazy">
      </button>
      <figcaption><span class="photo__title">Glacier National Park</span><span class="photo__place">Montana</span></figcaption>
    </figure>
    <figure class="photo" style="--ratio: 1.503">
      <button class="photo__frame" type="button" data-full="/images/photography/DSC_5425-2.jpg" data-caption="Arches National Park · Utah">
        <img src="/images/photography/DSC_5425-2.jpg" alt="Arches National Park, Utah" loading="lazy">
      </button>
      <figcaption><span class="photo__title">Arches National Park</span><span class="photo__place">Utah</span></figcaption>
    </figure>
  </div>
</div>

## Campus &amp; City

<div class="photo-rows">
  <div class="photo-row">
    <figure class="photo" style="--ratio: 3.0">
      <button class="photo__frame" type="button" data-full="/images/photography/seattle_skyline_pano.jpg" data-caption="Seattle Skyline · Washington">
        <img src="/images/photography/seattle_skyline_pano.jpg" alt="Seattle Skyline, Washington" loading="lazy">
      </button>
      <figcaption><span class="photo__title">Seattle Skyline</span><span class="photo__place">Washington</span></figcaption>
    </figure>
  </div>
  <div class="photo-row">
    <figure class="photo" style="--ratio: 1.5">
      <button class="photo__frame" type="button" data-full="/images/photography/memorial_union_terrace.jpg" data-caption="Memorial Union Terrace · Madison, Wisconsin">
        <img src="/images/photography/memorial_union_terrace.jpg" alt="Memorial Union Terrace, Madison, Wisconsin" loading="lazy">
      </button>
      <figcaption><span class="photo__title">Memorial Union Terrace</span><span class="photo__place">Madison, Wisconsin</span></figcaption>
    </figure>
    <figure class="photo" style="--ratio: 2.092">
      <button class="photo__frame" type="button" data-full="/images/photography/soochow_university.jpg" data-caption="Soochow University · Suzhou, China">
        <img src="/images/photography/soochow_university.jpg" alt="Soochow University, Suzhou, China" loading="lazy">
      </button>
      <figcaption><span class="photo__title">Soochow University</span><span class="photo__place">Suzhou, China</span></figcaption>
    </figure>
  </div>
</div>

<dialog class="lightbox" aria-label="Photo viewer">
  <img alt="">
  <p class="lightbox__caption"></p>
</dialog>

<script>
  (function () {
    const box = document.querySelector('.lightbox');
    const img = box.querySelector('img');
    const cap = box.querySelector('.lightbox__caption');
    document.querySelectorAll('.photo__frame').forEach(function (btn) {
      btn.addEventListener('click', function () {
        img.src = btn.dataset.full;
        img.alt = btn.dataset.caption;
        cap.textContent = btn.dataset.caption;
        box.showModal();
      });
    });
    box.addEventListener('click', function () { box.close(); });
  })();
</script>
