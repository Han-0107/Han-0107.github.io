---
show: true
width: 12
date: 2024-01-12 00:01:00 +0800
---
<div class="card h-100">
  <img src="{{ '/assets/images/empty_300x200.png' | relative_url }}" 
       data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" 
       class="lazy w-100 rounded-sm"
       loading="lazy">

  <div class="card-img-overlay" style="overflow-y: auto; max-height: 300px; background: rgba(255,255,255,0.8)">
    <h2>Welcome to Showcase!</h2>
    <hr />
    <p><code>Showcase</code> is a page...</p>
    <p>You can create a new...</p>
    <p>Cards are ordered by...</p>
    <p>For a tidy layout...</p>
  </div> <!-- 正确闭合 -->
</div>
