---
layout: default
title: Contact
permalink: /contact/
---

# Contact Me

I'm always open to discussing new projects or opportunities. Feel free to reach out!

## Get in Touch

- **Email:** [luca.borruto@gmail.com](mailto:luca.borruto@gmail.com)
- **GitHub:** [lborruto](https://github.com/lborruto)
- **LinkedIn:** [Luca Borruto](https://www.linkedin.com/in/lborruto/)

## Contact Form

<form
  action="https://formspree.io/f/xnnqgjnn"
  method="POST"
  class="contact-form"
>
  <label>
    <span>Your Email:</span>
    <input type="email" name="email" required />
  </label>
  <label>
    <span>Your Message:</span>
    <textarea name="message" rows="5" required></textarea>
  </label>
  <button type="submit">Send</button>
</form>

<style>
/* Contact Form Styling */
.contact-form {
  max-width: 600px;
  margin: 2rem auto;
  padding: 1.5rem;
  border: 1px solid #444;
  border-radius: 8px;
  background-color: #2c2c2c; /* Matches Dark Poole background */
  color: #f5f5f5; /* Matches text color */
  font-family: inherit;
}

.contact-form label {
  display: block;
  margin-bottom: 1rem;
}

.contact-form span {
  display: block;
  font-size: 1rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 0.75rem;
  font-size: 1rem;
  color: #f5f5f5;
  background-color: #1e1e1e; /* Dark input box */
  border: 1px solid #555;
  border-radius: 5px;
}

.contact-form input:focus,
.contact-form textarea:focus {
  outline: none;
  border-color: #888;
  box-shadow: 0 0 5px #888;
}

.contact-form button {
  display: block;
  width: 100%;
  padding: 0.75rem;
  font-size: 1rem;
  color: #fff;
  background-color: #007acc; /* Accent color */
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact-form button:hover {
  background-color: #005f99; /* Darker accent on hover */
}
</style>