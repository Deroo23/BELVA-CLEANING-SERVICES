# BELVA-CLEANING-SERVICES
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Belva Cleaning Services</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #00796b;
      color: white;
      padding: 2rem 1.5rem 1rem;
      text-align: center;
      position: relative;
    }

    header img.logo {
      width: 80px;
      height: auto;
      position: absolute;
      top: 10px;
      left: 10px;
    }

    nav {
      background-color: #004d40;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      padding: 0.75rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }

    h2 {
      color: #00796b;
      margin-bottom: 1rem;
    }

    .services li {
      margin-bottom: 0.5rem;
    }

    form input, form textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      background-color: #00796b;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      cursor: pointer;
      border-radius: 5px;
      font-size: 1rem;
    }

    iframe {
      width: 100%;
      height: 350px;
      border: none;
      margin-top: 1rem;
    }

    .contact-buttons {
      margin-top: 1rem;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .contact-buttons a {
      padding: 0.75rem 1rem;
      border-radius: 5px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      display: inline-block;
    }

    .whatsapp {
      background-color: #25D366;
    }

    .call {
      background-color: #00796b;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eeeeee;
      color: #555;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }

      form input, form textarea, form button {
        font-size: 1rem;
      }

      header img.logo {
        position: static;
        display: block;
        margin: 0 auto 1rem;
      }

      section {
        padding: 1rem;
      }

      .contact-buttons {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <header>
    <!-- Logo Placeholder -->
    <img src="logo.png" alt="Belva Logo" class="logo" />
    <h1>Belva Cleaning Services</h1>
    <p>Professional & Reliable Cleaning Services in Your Area</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
    <a href="#location">Location</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>
      Belva Cleaning Services offers high-quality residential and commercial cleaning in Nairobi. 
      Based at 87 Junction, Waiyaki Way, we are a trusted and fully insured team dedicated to making homes and businesses spotless and stress-free.
    </p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul class="services">
      <li>✔ House Cleaning</li>
      <li>✔ Office & Commercial Cleaning</li>
      <li>✔ Deep Cleaning</li>
      <li>✔ Move-In / Move-Out Cleaning</li>
      <li>✔ Regular Cleaning Plans</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form onsubmit="submitForm(event)">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="4" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p>
      Email: Jayd54649@gmail.com<br>
      Phone: 0741 108 721 / 0704 781 703<br>
      Location: 87 Junction, Waiyaki Way, Nairobi
    </p>

    <div class="contact-buttons">
      <a href="https://wa.me/254741108721" target="_blank" class="whatsapp">📱 WhatsApp Us</a>
      <a href="tel:+254741108721" class="call">📞 Call Now</a>
    </div>
  </section>

  <section id="location">
    <h2>Our Location</h2>
    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15955.67349723485!2d36.7322893!3d-1.2567279!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x182f1736f3bfb3a1%3A0x534b754fd78f10f4!2s87%20Junction%2C%20Waiyaki%20Way!5e0!3m2!1sen!2ske!4v1680000000000!5m2!1sen!2ske" 
      allowfullscreen="" 
      loading="lazy" 
      referrerpolicy="no-referrer-when-downgrade">
    </iframe>
  </section>

  <footer>
    &copy; 2025 Belva Cleaning Services. All rights reserved.
  </footer>

  <script>
    function submitForm(event) {
      event.preventDefault();
      alert('Thank you for contacting Belva Cleaning Services! We’ll get back to you shortly.');
    }
  </script>

</body>
</html>
