<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Package Protect</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f4f6f8;
      color: #333;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 2em 1em;
      text-align: center;
    }
    nav {
      background-color: #003366;
      display: flex;
      justify-content: center;
      padding: 1em;
    }
    nav a {
      color: white;
      margin: 0 1em;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      padding: 2em;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 3em;
    }
    h2 {
      color: #004080;
    }
    ul {
      list-style-type: square;
      padding-left: 1.5em;
    }
    form {
      background-color: #fff;
      padding: 2em;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 1em;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      padding: 0.8em;
      margin-top: 0.5em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 1.5em;
      padding: 0.8em 2em;
      background-color: #004080;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #003366;
    }
    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 1.5em;
      margin-top: 3em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Package Protect</h1>
    <p>Secure. Reliable. Protected.</p>
  </header>
  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#interest">Get in Touch</a>
  </nav>
  <main>
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Parcel Insurance for Domestic & International Shipments</li>
        <li>Real-Time GPS Tracking</li>
        <li>Secure Packaging & Tamper-Proof Seals</li>
        <li>Loss, Theft & Damage Coverage</li>
        <li>Business Integration for E-commerce Platforms</li>
      </ul>
    </section>
    <section id="about">
      <h2>About Us</h2>
      <p>At Package Protect, we believe every delivery deserves peace of mind. Whether you're sending a gift across town or shipping inventory across the globe, our mission is to ensure your packages arrive safely, securely, and on time. Trusted by thousands of businesses and individuals, we combine cutting-edge technology with unbeatable customer service.</p>
    </section>
    <section id="interest">
      <h2>Interested in Our Services?</h2>
      <form>
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" required />

        <label for="company">Company Name (optional)</label>
        <input type="text" id="company" name="company" />

        <label for="message">Tell us what you're looking for</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Submit Interest</button>
      </form>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Package Protect. All rights reserved.</p>
    <p>Contact: support@packageprotect.com | (800) 555-1234</p>
  </footer>
</body>
</html>
