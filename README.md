<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pro Property Maintenance</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      line-height: 1.6;
      color: #333;
      background: #F5F5F5; /* Light gray background */
    }

    header {
      background: #2E7D32; /* Forest green */
      color: white;
      padding: 1rem;
      display: flex;
      align-items: center;
    }

    header img {
      max-width: 150px; /* Consistent size */
      height: auto;
      margin-right: 1rem; /* Space between logo and text */
    }

    header h1 {
      font-size: 2.5rem; /* Bigger text */
      margin: 0;
    }

    nav {
      background: #4CAF50; /* Lighter green */
      padding: 1rem;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1.5rem;
      font-size: 1.2rem;
    }

    nav a:hover {
      color: #E8F5E9; /* Light green on hover */
    }

    .hero {
      background: #E8F5E9; /* Light green background */
      padding: 3rem 1rem;
      text-align: center;
    }

    .hero h1 {
      font-size: 2.5rem;
      color: #2E7D32; /* Forest green */
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.3rem;
      max-width: 700px;
      margin: 0 auto;
    }

    .section {
      padding: 2rem;
      max-width: 900px;
      margin: 0 auto;
    }

    .section h2 {
      font-size: 2rem;
      color: #2E7D32; /* Forest green */
      margin-bottom: 1rem;
    }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }

    .service-item {
      background: #EEEEEE; /* Slightly darker gray for service items */
      padding: 1.5rem;
      border-radius: 8px;
      text-align: center;
    }

    .service-item h3 {
      font-size: 1.5rem;
      margin-bottom: 0.5rem;
      color: #2E7D32; /* Forest green */
    }

    .contact-info {
      text-align: center;
      margin-top: 1rem;
      font-size: 1.2rem;
    }

    .social-links {
      margin-top: 1rem;
      font-size: 1.2rem;
    }

    .social-links a {
      color: #2E7D32; /* Forest green */
      text-decoration: none;
      margin: 0 0.5rem;
    }

    .social-links a:hover {
      color: #388E3C; /* Slightly lighter green */
    }

    footer {
      background: #2E7D32; /* Forest green */
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 1.8rem;
      }

      .hero p {
        font-size: 1.1rem;
      }

      nav a {
        display: block;
        margin: 0.5rem 0;
      }

      .section h2 {
        font-size: 1.8rem;
      }

      header {
        flex-direction: column;
        text-align: center;
      }

      header img {
        margin-right: 0;
        margin-bottom: 0.5rem;
      }

      header h1 {
        font-size: 2rem; /* Adjusted for mobile stacking */
      }

      .contact-info,
      .social-links {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo2-transparent.png" alt="Pro Property Maintenance Logo">
    <h1>Pro Property Maintenance</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="hero">
    <h1>Reliable Lawn Care & Property Services</h1>
    <p>We take care of your lawn, pressure washing, and bin cleaning so you don’t have to. We get down and dirty so you won't have to!</p>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>At Pro Property Maintenance, we’re committed to keeping your property in top shape. With years of experience, we offer professional lawn care, pressure washing, and bin washing services. Our team takes pride in delivering reliable, high-quality results that enhance your home’s curb appeal. Whether you’re a homeowner, renter, or property manager, we’re here to make maintenance easy and stress-free.</p>
  </section>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <div class="services-grid">
      <div class="service-item">
        <h3>Lawn Care</h3>
        <p>Keep your lawn looking its best with our mowing, edging, and trimming services. We ensure a neat, healthy yard that enhances your property’s appearance.</p>
      </div>
      <div class="service-item">
        <h3>Pressure Washing</h3>
        <p>Remove dirt, grime, and stains from driveways, decks, and siding with our powerful pressure washing. A clean exterior boosts your home’s value and appeal.</p>
      </div>
      <div class="service-item">
        <h3>Bin Washing</h3>
        <p>Eliminate odors and bacteria with our bin washing service. We clean and deodorize your bins, leaving them fresh, hygienic, and ready for use.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p class="contact-info">Call and text us at <strong>0422767150</strong> to book your service!</p>
    <div class="social-links">
      <p>Follow us on social media:</p>
      <a href="https://www.tiktok.com/@pro.propertymaintenance" target="_blank">TikTok: @pro.propertymaintenance</a> |
      <a href="https://www.instagram.com/pro.property.maintenance" target="_blank">Instagram: @pro.property.maintenance</a> |
      <a href="https://www.facebook.com/propropertymaintenance" target="_blank">Facebook: pro property maintenance</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Pro Property Maintenance. All rights reserved.</p>
  </footer>
</body>
</html>
