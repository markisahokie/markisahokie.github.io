---
# _pages/contact.md
layout: default
title: Contact Us
permalink: /contact/
---

# Contact ALPFA at Virginia Tech

We'd love to hear from you! Whether you have questions about membership, events, partnerships, or just want to say hello, feel free to reach out using the information below or the form.

## Get in Touch

### General Inquiries
*   **Email:** vtalpfa@gmail.com <!-- TODO: Replace with actual email -->
*   **Social Media:** Find us on [LinkedIn](https://www.linkedin.com/company/alpfavt), [Instagram](https://www.instagram.com/vtalpfa), [GobblerConnect](https://gobblerconnect.vt.edu/organization/alpfaatvt), and [LinkTree](https://linktr.ee/vtalpfa) (links also in footer).


---

## Send Us a Message

<form id="contact-form" action="mailto:info@alpfa-gothamcity.org?subject=Contact%20from%20Website" method="post" enctype="text/plain"> <!-- TODO: Replace with actual email -->
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="subject">Subject:</label>
  <input type="text" id="subject" name="subject" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit" class="btn">Send Message</button>
</form>

<script>
  // Optional: Prevent default submission and show a confirmation message
  document.getElementById('contact-form').addEventListener('submit', function(event) {
    // Note: mailto: links rely on the user's email client and may not always work as expected.
    // For a more robust solution, consider using a service like Netlify Forms or Formspree.
    alert('Thank you for your message! We will get back to you soon.');
    // Optionally, you could reset the form after submission
    // this.reset();
  });
</script>
