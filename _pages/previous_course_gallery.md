---
#layout: splash
title: "Gallery"
permalink: /previous_course_gallery/
---

<link rel="stylesheet" href="{{ '/assets/css/gallery.css' | relative_url }}">

{% include masonry-gallery.html images=site.data.gallery %}

<!-- {% raw %}{% assign images = site.static_files | where_exp: "file", "file.path contains '/assets/images/gallery/'" %} {% endraw %}-->

<!-- 
<div class="masonry-gallery">
  <div class="gallery-item">
    <img src="{{ '/assets/images/UMF_radio.JPG' | relative_url }}" alt="Image 1">
  </div>

  <div class="gallery-item">
    <img src="{{ '/assets/images/UMF_radio.JPG' | relative_url }}" alt="Image 2">
  </div>

  <div class="gallery-item">
    <img src="{{ '/assets/images/UMF_radio.JPG' | relative_url }}" alt="Image 3">
  </div>
</div>
-->
