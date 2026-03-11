---
layout: single
title: "Pictures"
permalink: /pictures/
author_profile: true
---

Wisdom comes from thought

<div class="gallery">
  <img src="/images/my_photo/1.jpg" alt="Photo 1">
  
  <img src="/images/my_photo/3.jpg" alt="Photo 3">
  <img src="/images/my_photo/4.jpg" alt="Photo 4">
  <img src="/images/my_photo/5.jpg" alt="Photo 5">
  <img src="/images/my_photo/6.jpg" alt="Photo 6">
  <img src="/images/my_photo/7.jpg" alt="Photo 7">
  <img src="/images/my_photo/8.jpg" alt="Photo 8">
  <img src="/images/my_photo/2.jpg" alt="Photo 2">
  <img src="/images/my_photo/9.jpg" alt="Photo 9">
</div>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 20px;
  margin-top: 20px;
}
.gallery img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
</style>
