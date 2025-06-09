---
layout: page
title: "Contact"
permalink: /contact/
---

<form action="https://formspree.io/f/mrbkpyjq" method="POST">
  <div class="form-group">
    <label for="contact-name">Name</label>
    <input id="contact-name" name="name" type="text" required>
  </div>

  <div class="form-group">
    <label for="contact-email">Email</label>
    <input id="contact-email" name="email" type="email" required>
  </div>

  <div class="form-group">
    <label for="contact-message">Message</label>
    <textarea id="contact-message" name="message" rows="5" required></textarea>
  </div>

  <button type="submit">Send</button>
</form>