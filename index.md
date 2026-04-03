---
layout: default
title: Home
---

<!-- HERO -->
<section class="hero">
  <h1>Rida Batool – Frontend Practice Journal</h1>
  <p>I am a beginner student building simple and responsive web pages using HTML, CSS, and JavaScript. This blog shows my practice work and weekly progress.</p>
  <div class="hero-btns">
    <a href="{{ '/blog' | relative_url }}" class="btn-primary">Read Lab Articles</a>
    <a href="{{ '/about' | relative_url }}" class="btn-ghost">About Me</a>
  </div>
</section>

<!-- LATEST ARTICLES -->
<section>
  <div class="section-heading">
    <h2>Latest Practice Articles</h2>
    <p>Simple notes from my weekly learning and university lab tasks.</p>
  </div>

  <article class="article-card">
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
        <a href="{{ '/blog' | relative_url }}" class="btn-read-more">Read More</a>
      </div>
    </div>
  </article>

  <article class="article-card">
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
        <a href="{{ '/blog' | relative_url }}" class="btn-read-more">Read More</a>
      </div>
    </div>
  </article>

  <article class="article-card">
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
        <a href="{{ '/blog' | relative_url }}" class="btn-read-more">Read More</a>
      </div>
    </div>
  </article>

</section>
