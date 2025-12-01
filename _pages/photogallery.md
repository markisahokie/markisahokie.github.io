---
layout: default
title: Photo Gallery
---

# Photo Gallery

<!-- Carousel HTML + CSS + JS below -->
<style>
.carousel {
  max-width: 800px;
  margin: 2rem auto;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
.carousel-inner {
  display: flex;
  transition: transform 0.4s ease-in-out;
}
.carousel-item {
  min-width: 100%;
}
.carousel-item img {
  width: 100%;
  display: block;
}
.controls {
  text-align: center;
  margin-top: 1rem;
}
.controls button {
  margin: 0 0.5rem;
  padding: 0.5rem 1rem;
  font-size: 1rem;
}
</style>

<div class="carousel">
  <div class="carousel-inner" id="carousel">
    <div class="carousel-item"><img src="/assets/img/Gal1.JPG" alt="Photo 1"></div>
    <div class="carousel-item"><img src="/assets/img/Gal2.JPG" alt="Photo 2"></div>
    <div class="carousel-item"><img src="/assets/img/Gal3.JPG" alt="Photo 3"></div>
    <div class="carousel-item"><img src="/assets/img/Gal4.JPG" alt="Photo 1"></div>
    <div class="carousel-item"><img src="/assets/img/Gal5.jpeg" alt="Photo 2"></div>
    <div class="carousel-item"><img src="/assets/img/Gal6.jpeg" alt="Photo 3"></div>
    <div class="carousel-item"><img src="/assets/img/Gal7.jpeg" alt="Photo 1"></div>
    <div class="carousel-item"><img src="/assets/img/Gal8.jpeg" alt="Photo 2"></div>
    <div class="carousel-item"><img src="/assets/img/Gal9.JPG" alt="Photo 3"></div>
    <div class="carousel-item"><img src="/assets/img/Gal10.jpeg" alt="Photo 1"></div>
    <div class="carousel-item"><img src="/assets/img/Gal11.JPG" alt="Photo 2"></div>
    <div class="carousel-item"><img src="/assets/img/exec-all.JPG" alt="Photo 3"></div
  </div>
  <div class="controls">
    <button onclick="prevSlide()">❮</button>
    <button onclick="nextSlide()">❯</button>
  </div>
</div>

<script>
let currentIndex = 0;
const items = document.querySelectorAll('.carousel-item');
const total = items.length;

function showSlide(index) {
  if (index >= total) currentIndex = 0;
  else if (index < 0) currentIndex = total - 1;
  else currentIndex = index;
  document.getElementById('carousel').style.transform = `translateX(-${currentIndex * 100}%)`;
}

function nextSlide() { showSlide(currentIndex + 1); }
function prevSlide() { showSlide(currentIndex - 1); }

// Optional: auto-advance every 4 seconds
setInterval(nextSlide, 4000);
</script>
