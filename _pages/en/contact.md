---
layout: page
title: Contact
permalink: /en/contact/
lang: en
---

<h1>{{ page.title }}</h1>

<div class="wrapper">
  <p>Feel free to reach out to me via email at <a href="mailto:noah.tonnesen@gmail.com">noah.tonnesen@gmail.com</a>. Alternatively, you can fill out the contact form below:</p>

  <form action="https://formspree.io/f/mnnqojon" method="POST">
    <div style="margin-bottom: 15px;">
      <label for="email" style="display: block; margin-bottom: 5px;">Your email:</label>
      <input type="email" id="email" name="email" required>
    </div>
    
    <div style="margin-bottom: 15px;">
      <label for="name" style="display: block; margin-bottom: 5px;">Your name:</label>
      <input type="name" id="name" name="name" required>
    </div>
    
    <div style="margin-bottom: 15px;">
      <label for="message" style="display: block; margin-bottom: 5px;">Your message:</label>
      <textarea id="message" name="message" required style="height: 150px;"></textarea>
    </div>
    
    <div style="text-align: center;">
      <button type="submit">Send</button>
    </div>
  </form>
</div>