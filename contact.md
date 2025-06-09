---
layout: page
title: "Contact"
permalink: /contact/
---

<div class="contact-hero">
  <h1>{{ page.title }}</h1>
  <p class="contact-subtitle">Let's talk — send me a message below!</p>
</div>

<div class="contact-form-wrapper">
  <form action="https://formspree.io/f/abcd1234" method="POST" class="contact-form">
    <div class="form-group">
      <label for="contact-name">Name</label>
      <input id="contact-name" name="name" type="text" placeholder="Your name" required>
    </div>

    <div class="form-group">
      <label for="contact-email">Email</label>
      <input id="contact-email" name="email" type="email" placeholder="you@example.com" required>
    </div>

    <div class="form-group">
      <label for="contact-message">Message</label>
      <textarea id="contact-message" name="message" rows="5" placeholder="What’s on your mind?" required></textarea>
    </div>

    <button type="submit" class="btn">Send</button>
  </form>
</div>