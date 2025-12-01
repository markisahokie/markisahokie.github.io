---
layout: default
title: Contact Us
permalink: /contact/
---

<div class="contact-container">
  
  <h1>Contact ALPFA at Virginia Tech</h1>
  <p class="intro">
    We'd love to hear from you! Whether you have questions about membership, events, partnerships, or just want to say hello, feel free to reach out.
  </p>

  <hr class="divider">

  <!-- Contact Information Section -->
  <section class="contact-section">
    <h2>Get in Touch</h2>
    
    <div class="contact-info">
      <h3>General Inquiries</h3>
      <p>
        <strong>Email:</strong> 
        <a href="mailto:vtalpfa@gmail.com">vtalpfa@gmail.com</a>
      </p>
      <p>
        <strong>Social Media:</strong> Find us on 
        <a href="https://www.linkedin.com/company/alpfavt" target="_blank" rel="noopener">LinkedIn</a>, 
        <a href="https://www.instagram.com/vtalpfa" target="_blank" rel="noopener">Instagram</a>, 
        <a href="https://gobblerconnect.vt.edu/organization/alpfaatvt" target="_blank" rel="noopener">GobblerConnect</a>, and 
        <a href="https://linktr.ee/vtalpfa" target="_blank" rel="noopener">LinkTree</a>
      </p>
    </div>
  </section>

  <hr class="divider">

  <!-- Contact Form Section -->
  <section class="contact-section">
    <h2>Send Us a Message</h2>
    
    <form id="contact-form" class="contact-form" action="mailto:vtalpfa@gmail.com?subject=Contact%20from%20Website" method="post" enctype="text/plain">
      
      <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
      </div>

      <div class="form-group">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
      </div>

      <div class="form-group">
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject" required>
      </div>

      <div class="form-group">
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="6" required></textarea>
      </div>

      <button type="submit" class="btn-submit">Send Message</button>
    </form>

    <p class="form-note">
      <strong>Note:</strong> This form uses your default email client. For a more reliable contact form, consider using 
      <a href="https://formspree.io/" target="_blank" rel="noopener">Formspree</a> or 
      <a href="https://docs.netlify.com/forms/setup/" target="_blank" rel="noopener">Netlify Forms</a>.
    </p>
  </section>

</div>

<script>
  document.getElementById('contact-form').addEventListener('submit', function(event) {
    alert('Thank you for your message! We will get back to you soon.');
  });
</script>
