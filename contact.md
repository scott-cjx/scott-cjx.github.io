---
title: Contact Me
---

# Contact Me

I’d love to hear from you! Please fill out the form below to get in touch with me.

## Contact Form

<div class="contact-form">
  <form action="https://formspree.io/f/{your-form-id}" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required placeholder="Your Name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required placeholder="Your Email">

    <label for="message">Message:</label>
    <textarea id="message" name="message" required placeholder="Your Message"></textarea>

    <button type="submit">Send Message</button>
  </form>
</div>

<style>
  /* Basic styling for the page */
  body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
  }

  h1, h2 {
      text-align: center;
      color: #2c3e50;
  }

  .contact-form {
      max-width: 600px;
      margin: 30px auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  form {
      display: flex;
      flex-direction: column;
  }

  label {
      margin-bottom: 8px;
      font-weight: bold;
      color: #34495e;
  }

  input, textarea {
      padding: 12px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 5px;
      font-size: 16px;
  }

  input[type="text"], input[type="email"] {
      height: 40px;
  }

  textarea {
      resize: vertical;
      height: 150px;
  }

  button {
      padding: 12px;
      background-color: #3498db;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
  }

  button:hover {
      background-color: #2980b9;
  }

  button:focus {
      outline: none;
  }
</style>
