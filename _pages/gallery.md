---
title: "Gallery"
permalink: /gallery/
layout: splash
author_profile: false
---

<style>
.gallery-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 20px;
}
.gallery-item {
  width: calc(33.33% - 20px); /* Three items per row with gap */
  box-sizing: border-box;
  text-align: center;
}
.gallery-item img {
  width: 100%;
  height: auto; /* Maintain aspect ratio */
  object-fit: cover; /* Ensure images cover the space without distortion */
  border-radius: 8px;
}
.gallery-item p {
  margin-top: 10px;
  font-size: 16px;
}
@media (max-width: 992px) {
  .gallery-item {
    width: calc(50% - 20px); /* Two items per row on medium screens */
  }
}
@media (max-width: 768px) {
  .gallery-item {
    width: calc(100% - 20px); /* One item per row on smaller screens */
  }
}
</style>

<div class="gallery-container">
  <div class="gallery-item">
    <img src="../images/gallery/convocation2.jpg" alt="Awarded the MTech">
    <p>Awarded the MTech in Computer Science and Engineering at IITGN convocation June 2024</p>
  </div>
  <div class="gallery-item">
    <img src="../images/gallery/convocation.jpg" alt="Outside IITGN Convocation Hall 2024">
    <p>Outside IITGN Convocation Hall June 2024</p>
  </div>
    <div class="gallery-item">
    <img src="../images/gallery/convocation3.jpg" alt="Outside IITGN Convocation Hall 2024">
    <p>Outside IITGN Convocation Hall with my family</p>
  </div>
  <div class="gallery-item">
    <img src="../images/gallery/MtechThesisDefense.jpg" alt="2024 June Mtech defense">
    <p>Suraj (left) and I are celebrating the successful defense of our MTech thesis</p>
  </div>
  <!-- Add more images here with descriptions -->
</div>
