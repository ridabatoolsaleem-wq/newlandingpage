---
layout: default
title: Blog
---

<div class="page-header">
  <h1>All Articles</h1>
  <p>My weekly practice notes, lab tasks, and learning logs.</p>
</div>

<div class="filters">
  <button class="filter-btn active" onclick="filterCards(this, 'all')">All</button>
  <button class="filter-btn" onclick="filterCards(this, 'lab')">Lab Project</button>
  <button class="filter-btn" onclick="filterCards(this, 'css')">CSS Practice</button>
  <button class="filter-btn" onclick="filterCards(this, 'js')">JavaScript</button>
</div>

<article class="article-card" data-cat="lab">
  <img class="thumb" src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=400&q=80" alt="Lab Website">
  <div class="card-body">
    <div>
      <div class="card-top">
        <span class="tag tag-lab">Lab Project</span>
        <span class="date">20 Mar 2026</span>
      </div>
      <p class="card-title">Building My First Lab Website</p>
      <p class="card-desc">My first complete website submission using HTML, CSS, and a little JavaScript with responsive design.</p>
    </div>
    <div class="card-footer">
      <span class="read-time">6 min read</span>
      <a href="#" class="btn-read-more">Read More</a>
    </div>
  </div>
</article>

<article class="article-card" data-cat="css">
  <img class="thumb" src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=400&q=80" alt="CSS Layout">
  <div class="card-body">
    <div>
      <div class="card-top">
        <span class="tag tag-css">CSS Practice</span>
        <span class="date">25 Mar 2026</span>
      </div>
      <p class="card-title">What I Learned from CSS Layout Practice</p>
      <p class="card-desc">A simple note on using Flexbox and spacing rules to make beginner websites look cleaner and easier to read.</p>
    </div>
    <div class="card-footer">
      <span class="read-time">7 min read</span>
      <a href="#" class="btn-read-more">Read More</a>
    </div>
  </div>
</article>

<article class="article-card" data-cat="js">
  <img class="thumb" src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=400&q=80" alt="JavaScript">
  <div class="card-body">
    <div>
      <div class="card-top">
        <span class="tag tag-js">JavaScript</span>
        <span class="date">30 Mar 2026</span>
      </div>
      <p class="card-title">My First JavaScript DOM Exercise</p>
      <p class="card-desc">Practicing basic DOM manipulation — clicking buttons, changing text, and showing/hiding elements with JavaScript.</p>
    </div>
    <div class="card-footer">
      <span class="read-time">5 min read</span>
      <a href="#" class="btn-read-more">Read More</a>
    </div>
  </div>
</article>

<article class="article-card" data-cat="css">
  <img class="thumb" src="https://images.unsplash.com/photo-1621839673705-6617adf9e890?w=400&q=80" alt="Responsive Design">
  <div class="card-body">
    <div>
      <div class="card-top">
        <span class="tag tag-css">CSS Practice</span>
        <span class="date">2 Apr 2026</span>
      </div>
      <p class="card-title">Making Websites Responsive with Media Queries</p>
      <p class="card-desc">Learning how to use CSS media queries to make web pages look good on mobile phones and tablets.</p>
    </div>
    <div class="card-footer">
      <span class="read-time">8 min read</span>
      <a href="#" class="btn-read-more">Read More</a>
    </div>
  </div>
</article>

<script>
function filterCards(btn, cat) {
  document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  document.querySelectorAll('.article-card').forEach(card => {
    card.style.display = (cat === 'all' || card.dataset.cat === cat) ? 'grid' : 'none';
  });
}
</script>
