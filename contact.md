---
layout: default
title: Contact
permalink: /contact/
---

<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.1/css/bootstrap.min.css"
/>

# Contact Me

I'm always open to discussing new projects or opportunities. Feel free to reach out!

## Get in Touch

- **Email:** [luca.borruto@gmail.com](mailto:luca.borruto@gmail.com)
- **GitHub:** [lborruto](https://github.com/lborruto)
- **LinkedIn:** [Luca Borruto](https://www.linkedin.com/in/lborruto/)

## Contact Form

<div class="container mt-4">
  <form
    action="https://formspree.io/f/xnnqgjnn"
    method="POST"
    class="needs-validation"
    novalidate
  >
    <div class="mb-3">
      <label for="email" class="form-label">Your Email:</label>
      <input
        type="email"
        class="form-control"
        id="email"
        name="email"
        placeholder="Enter your email"
        required
      />
      <div class="invalid-feedback">Please enter a valid email.</div>
    </div>
    <div class="mb-3">
      <label for="message" class="form-label">Your Message:</label>
      <textarea
        class="form-control"
        id="message"
        name="message"
        rows="5"
        placeholder="Write your message here"
        required
      ></textarea>
      <div class="invalid-feedback">Message cannot be empty.</div>
    </div>
    <button type="submit" class="btn btn-primary w-100">Send Message</button>
  </form>
</div>

<script>
  // Bootstrap validation script
  (function () {
    "use strict";
    const forms = document.querySelectorAll(".needs-validation");
    Array.prototype.slice.call(forms).forEach(function (form) {
      form.addEventListener(
        "submit",
        function (event) {
          if (!form.checkValidity()) {
            event.preventDefault();
            event.stopPropagation();
          }
          form.classList.add("was-validated");
        },
        false
      );
    });
  })();
</script>