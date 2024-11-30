---
layout: page
title: Contact
permalink: /fr/contact/
lang: fr
---

<h1>{{ page.title }}</h1>

<div class="wrapper">
  <p>N'hésitez pas à me contacter par email à <a href="mailto:noah.tonnesen@gmail.com">noah.tonnesen@gmail.com</a>. Vous pouvez également remplir le formulaire de contact ci-dessous:</p>

  <form action="https://formspree.io/f/mnnqojon" method="POST">
    <div style="margin-bottom: 15px;">
      <label for="email" style="display: block; margin-bottom: 5px;">Votre email:</label>
      <input type="email" id="email" name="email" required>
    </div>
    
    <div style="margin-bottom: 15px;">
      <label for="name" style="display: block; margin-bottom: 5px;">Votre nom:</label>
      <input type="name" id="name" name="name" required>
    </div>
    
    <div style="margin-bottom: 15px;">
      <label for="message" style="display: block; margin-bottom: 5px;">Votre message:</label>
      <textarea id="message" name="message" required style="height: 150px;"></textarea>
    </div>
    
    <div style="text-align: center;">
      <button type="submit">Envoyer</button>
    </div>
  </form>
</div>