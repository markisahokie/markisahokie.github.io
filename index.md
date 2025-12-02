---
# _pages/index.md
layout: default
title: Home
---

# ALPFA at Virginia Tech

## {{ site.description }}
<!-- 
<div style="margin-bottom: 2rem;">
    <img 
        src="{{ '/assets/img/Gal11.JPG' | relative_url }}" 
        alt="VT ALPFA"
        style="width: 100%; height: auto; display: block; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
</div>
-->
<style>
.carousel {
  max-width: 800px;
  margin: 2rem auto;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  background-color: #f5f5f5;
}
.carousel-inner {
  display: flex;
  transition: transform 0.4s ease-in-out;
}
.carousel-item {
  min-width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 400px;
}
.carousel-item img {
  max-width: 100%;
  max-height: 600px;
  width: auto;
  height: auto;
  display: block;
  object-fit: contain;
}
.controls {
  text-align: center;
  margin-top: 1rem;
}
.controls button {
  margin: 0 0.5rem;
  padding: 0.5rem 1rem;
  font-size: 1rem;
  cursor: pointer;
  background-color: #333;
  color: white;
  border: none;
  border-radius: 4px;
}
.controls button:hover {
  background-color: #555;
}
</style>
<div class="carousel">
  <div class="carousel-inner" id="carousel">
    <div class="carousel-item"><img src="/assets/img/Gal1.JPG" alt="Photo 1"></div>
    <div class="carousel-item"><img src="/assets/img/Gal2.JPG" alt="Photo 2"></div>
    <div class="carousel-item"><img src="/assets/img/Gal3.JPG" alt="Photo 3"></div>
    <div class="carousel-item"><img src="/assets/img/Gal4.JPG" alt="Photo 4"></div>
    <div class="carousel-item"><img src="/assets/img/Gal5.jpeg" alt="Photo 5"></div>
    <div class="carousel-item"><img src="/assets/img/Gal6.jpeg" alt="Photo 6"></div>
    <div class="carousel-item"><img src="/assets/img/Gal7.jpeg" alt="Photo 7"></div>
    <div class="carousel-item"><img src="/assets/img/Gal8.jpeg" alt="Photo 8"></div>
    <div class="carousel-item"><img src="/assets/img/Gal9.JPG" alt="Photo 9"></div>
    <div class="carousel-item"><img src="/assets/img/Gal10.jpeg" alt="Photo 10"></div>
    <div class="carousel-item"><img src="/assets/img/Gal11.JPG" alt="Photo 11"></div>
    <div class="carousel-item"><img src="/assets/img/exec-all.JPG" alt="Photo 12"></div>
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

### What is ALPFA Student Chapter at Virginia Tech?

#### Founded in 2015, ALPFA-VT is a student chapter of the national ALPFA  organization, dedicated to empowering underrepresented students through  leadership development, mentorship, and community. As a non-exclusive  business organization within the Pamplin College of Business, we connect  students with industry professionals, promote workforce diversity, and equip  members with the skills and networks to thrive in their careers.

### What is ALPFA? 

#### The Association of Latino Professionals for America (ALPFA) is the  longest-standing Latino national professional association, consisting of chapters across the United States and Puerto Rico. ALPFA is dedicated to  enhancing opportunities for Latinos across all industries, including business related professions.
#### [Learn More](https://www.alpfa.org)

###  Mission & Purpose
#### Mission Statement: To empower and develop ALL students as leaders of  character for the nation, in every sector of the global economy. 

#### Purpose Statement: To provide professional networking opportunities for such  professionals, and to advance their professional education goals.

### Upcoming Events

#### Check back soon for upcoming events and initiatives!

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; margin: 2rem 0;">
    <a href="https://your-link-1.com" target="_blank">
        <img src="/assets/img/exec-3.jpg" alt="Description 1" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s;">
    </a>
    <a href="https://your-link-2.com" target="_blank">
        <img src="/assets/img/exec-1.jpg" alt="Description 2" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s;">
    </a>
    <a href="https://your-link-3.com" target="_blank">
        <img src="/assets/img/exec-2.jpg" alt="Description 3" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s;">
    </a>
</div>

<style>
a img:hover {
    transform: scale(1.05);
    cursor: pointer;
}
</style>

### Become a leader of tomorrow. Join the #ALPFAmilia 

#### <a href="https://gobblerconnect.vt.edu/organization/alpfaatvt" target="_blank" rel="noopener">Become a Member</a>
#### <a href="https://tr.ee/IWSDL8Wd55" target="_blank" rel="noopener">Subscribe To Our Newsletter</a>
#### <a href="https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgobblerconnect.us17.list-manage.com%2Ftrack%2Fclick%3Fu%3D235348359a26562b5eba5607f%26id%3D9832254131%26e%3Da4de32db27&data=05%7C02%7Cmark05%40vt.edu%7C9060a42e95584e6f216808de26497ae7%7C6095688410ad40fa863d4f32c1e3a37a%7C0%7C0%7C638990294233383063%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=pONkpmqIKeGOo6xKrrSINo59VV%2BVEbJwZA1Wp37Qt%2Bg%3D&reserved=0" target="_blank" rel="noopener">Submit Your Resume</a>
