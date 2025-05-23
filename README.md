<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pit & Prairie Landscaping</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --dark-green: #0f3b2f;
      --light-tan: #e2d1a6;
      --accent-gold: #d4a55d;
      --white: #ffffff;
    }
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: var(--white);
      color: var(--dark-green);
    }
    header {
      background-color: var(--dark-green);
      color: var(--white);
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.3);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: var(--white);
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: 700;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: var(--accent-gold);
    }
    .hero {
      background: linear-gradient(rgba(15,59,47,0.85), rgba(15,59,47,0.85)), url('lawn-bg.jpg') center/cover no-repeat;
      color: var(--white);
      padding: 8rem 2rem;
      text-align: center;
    }
    .hero h1 {
      font-size: 3.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.5rem;
      margin-bottom: 2rem;
    }
    .cta-button {
      background-color: var(--accent-gold);
      color: var(--dark-green);
      padding: 1rem 2.5rem;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      font-size: 1.2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #c3914a;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      font-size: 2.5rem;
      margin-bottom: 2rem;
      color: var(--dark-green);
    }
    .service-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }
    .service {
      background-color: var(--light-tan);
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
      transition: transform 0.3s ease;
    }
    .service:hover {
      transform: translateY(-5px);
    }
    .contact form {
      display: grid;
      gap: 1rem;
    }
    form input, form textarea {
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }
    form button {
      background-color: var(--accent-gold);
      color: var(--dark-green);
      padding: 1rem;
      font-size: 1.1rem;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    form button:hover {
      background-color: #c3914a;
    }
    footer {
      background-color: var(--dark-green);
      color: var(--white);
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <div><img src="logo.png" alt="Pit & Prairie Logo" /></div>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Pit & Prairie Landscaping</h1>
    <p>Rugged, Reliable Landscaping in Gillette, WY</p>
    <a href="#contact" class="cta-button">Get a Free Estimate</a>
  </div>

  <section class="services" id="services">
    <h2>Our Services</h2>
    <div class="service-list">
      <div class="service">
        <h3>Lawn Mowing & Trimming</h3>
        <p>Keep your lawn clean and sharp all summer long.</p>
      </div>
      <div class="service">
        <h3>Yard Cleanup & Raking</h3>
        <p>Seasonal cleanup including raking and debris removal.</p>
      </div>
      <div class="service">
        <h3>Weed & Fertilizer Treatment</h3>
        <p>Healthy lawns start with proper care and prevention.</p>
      </div>
      <div class="service">
        <h3>Brush & Trash Removal</h3>
        <p>Clear unwanted debris fast — perfect for open yards or lots.</p>
      </div>
      <div class="service">
        <h3>Snow Removal</h3>
        <p>Driveways, sidewalks, and parking cleared promptly.</p>
      </div>
      <div class="service">
        <h3>Custom Landscape Design</h3>
        <p>Design and build the landscape of your dreams.</p>
      </div>
    </div>
  </section>

  <section class="about" id="about">
    <h2>About Us</h2>
    <p style="max-width: 800px; margin: auto; text-align: center; font-size: 1.2rem;">Started in Gillette, Pit & Prairie Landscaping is built on strong work ethic, local roots, and a passion for outdoor spaces. We serve residential and commercial clients with top-quality lawn care and seasonal services year-round.</p>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p style="text-align: center; font-size: 1.1rem;">Email: pitprairielandscaping@example.com | Phone: (555) 555-5555</p>
    <form>
      <input type="text" id="name" name="name" placeholder="Your Name" required>
      <input type="email" id="email" name="email" placeholder="Your Email" required>
      <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Pit & Prairie Landscaping. All rights reserved.</p>
  </footer>
</body>
</html>

