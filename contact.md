---
layout: default
title: Contact
---

<div class="page-header">
  <h1>Get in Touch</h1>
  <p>Have a question or want to share feedback? Send me a message!</p>
</div>

<div class="info-row">
  <div class="info-item">
    <div class="label">Location</div>
    <div class="value">Pakistan</div>
  </div>
  <div class="info-item">
    <div class="label">Studying</div>
    <div class="value">Computer Science</div>
  </div>
  <div class="info-item">
    <div class="label">Focus</div>
    <div class="value">Frontend Dev</div>
  </div>
</div>

<div class="contact-card">
  <div class="form-group">
    <label for="name">Your Name</label>
    <input type="text" id="name" placeholder="e.g. Sara Ahmed" />
  </div>
  <div class="form-group">
    <label for="email">Email Address</label>
    <input type="email" id="email" placeholder="sara@example.com" />
  </div>
  <div class="form-group">
    <label for="subject">Subject</label>
    <input type="text" id="subject" placeholder="What's this about?" />
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" placeholder="Write your message here..."></textarea>
  </div>
  <button class="btn-primary" onclick="sendMsg()">Send Message</button>
  <div class="success-msg" id="successMsg">✓ Message sent! I'll get back to you soon.</div>
</div>

<script>
function sendMsg() {
  var name = document.getElementById('name').value.trim();
  var email = document.getElementById('email').value.trim();
  var message = document.getElementById('message').value.trim();
  if (!name || !email || !message) {
    alert('Please fill in your name, email, and message.');
    return;
  }
  document.getElementById('successMsg').style.display = 'block';
  document.getElementById('name').value = '';
  document.getElementById('email').value = '';
  document.getElementById('subject').value = '';
  document.getElementById('message').value = '';
}
</script>
