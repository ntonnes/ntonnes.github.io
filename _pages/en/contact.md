---
layout: page
title: Contact
permalink: /en/contact/
lang: en
---
<style>
.wrapper {
    margin: 0 auto;
    max-width: 1000px;
    padding: 10px;
    font-size: 1.1em;
}
section {
    margin-top: 20px;
}
input, textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1.1em;
    box-sizing: border-box;
}
button[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1.1em;
    width: 100%; /* Ensure the submit button stretches horizontally */
}
button[type="submit"]:hover {
    background-color: #45a049;
}
form {
    max-width: 1000px; /* Match the width of the .wrapper */
    margin: 0 auto;
}
</style>

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