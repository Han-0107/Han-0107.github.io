---
show: true
width: 12
date: 2020-01-12 00:01:00 +0800
---
<div class="position-relative" style="padding-top: 66.66%;"> <!-- 3:2 比例 -->
  <img data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" 
       class="lazy rounded-sm position-absolute w-100 h-100"
       style="object-fit: cover"
       src="{{ '/assets/images/empty_600x400.png' | relative_url }}">
  
  <div class="card-img-overlay" style="bottom: 0; top: auto">
    <h2 class="card-title">Image Lazyload</h2>
    <p class="card-text">...</p>
  </div>
</div>
