<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="SerèneSource - Premium Spring Water from Pristine Sources">
  <title>SerèneSource - Premium Spring Water</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar">
    <div class="logo">
      <img src="assets/logo.png" alt="SerèneSource Logo" class="logo-img">
    </div>
    <ul class="nav-links">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#products">Products</a></li>
      <li><a href="#hydration">Hydration</a></li>
      <li><a href="#sustainability">Sustainability</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>SerèneSource</h1>
      <p>Pure Spring Water from Nature’s Finest Sources</p>
      <a href="#products" class="cta-button">Discover Our Waters</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>Our Story</h2>
    <p>SerèneSource is sourced from pristine, untouched springs, delivering unparalleled purity and natural minerals. Our mission is to provide sustainable hydration that nourishes both body and planet.</p>
  </section>

  <!-- Products Section -->
  <section id="products" class="products">
    <h2>Our Spring Waters</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="assets/still-water.jpg" alt="Still Spring Water">
        <h3>Still Spring Water</h3>
        <p>$2.99</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="assets/sparkling-water.jpg" alt="Sparkling Spring Water">
        <h3>Sparkling Spring Water</h3>
        <p>$3.49</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="assets/mineral-water.jpg" alt="Mineral-Enhanced Water">
        <h3>Mineral-Enhanced Water</h3>
        <p>$4.99</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
    </div>
  </section>

  <!-- Hydration Tips Section -->
  <section id="hydration" class="hydration">
    <h2>Hydration Tips</h2>
    <p>Maximize your wellness with these spring water hydration tips.</p>
    <div class="tips-grid">
      <div class="tip-card">
        <h3>Stay Consistent</h3>
        <p>Sip SerèneSource throughout the day for optimal hydration.</p>
      </div>
      <div class="tip-card">
        <h3>Pair with Nature</h3>
        <p>Enhance your water with fresh lemon or mint for a natural boost.</p>
      </div>
      <div class="tip-card">
        <h3>Listen to Your Body</h3>
        <p>Increase intake during exercise or hot weather.</p>
      </div>
    </div>
  </section>

  <!-- Sustainability Section -->
  <section id="sustainability" class="sustainability">
    <h2>Sustainability Matters</h2>
    <p>Our spring water is bottled in recyclable glass, and we partner with clean water initiatives to protect our planet’s precious resources.</p>
    <button class="learn-more">Learn More</button>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Get in Touch</h2>
    <form id="contact-form">
      <input type="text" name="name" placeholder="Name" required>
      <input type="email" name="email" placeholder="Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 SerèneSource. All rights reserved.</p>
  </footer>

  <!-- Embedded CSS -->
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      color: #023E8A;
      background-color: #F5FBFF;
      line-height: 1.6;
    }

    /* Navigation */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.5rem 2rem;
      background-color: #FFFFFF;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo-img {
      height: 3rem;
      transition: transform 0.3s ease;
    }

    .logo-img:hover {
      transform: scale(1.05);
    }

    .nav-links {
      display: flex;
      list-style: none;
      gap: 1.5rem;
    }

    .nav-links a {
      text-decoration: none;
      color: #0077B6;
      font-weight: 600;
      font-size: 1rem;
      transition: color 0.3s ease;
    }

    .nav-links a:hover {
      color: #90E0EF;
    }

    .hamburger {
      display: none;
      flex-direction: column;
      gap: 0.3rem;
      cursor: pointer;
    }

    .hamburger span {
      width: 1.8rem;
      height: 0.2rem;
      background-color: #0077B6;
      transition: all 0.3s ease;
    }

    .hamburger.active span:nth-child(1) {
      transform: rotate(45deg) translate(0.5rem, 0.5rem);
    }

    .hamburger.active span:nth-child(2) {
      opacity: 0;
    }

    .hamburger.active span:nth-child(3) {
      transform: rotate(-45deg) translate(0.5rem, -0.5rem);
    }

    /* Hero Section */
    .hero {
      min-height: 100vh;
      background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), url('assets/hero-bg.jpg') no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #FFFFFF;
      padding: 2rem;
    }

    .hero-content h1 {
      font-size: 3.5rem;
      font-weight: 700;
      margin-bottom: 1.5rem;
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.4);
    }

    .hero-content p {
      font-size: 1.25rem;
      margin-bottom: 2rem;
      max-width: 600px;
    }

    .cta-button {
      padding: 1rem 2rem;
      background-color: #0077B6;
      color: #FFFFFF;
      text-decoration: none;
      border-radius: 8px;
      font-weight: 600;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    .cta-button:hover {
      background-color: #90E0EF;
      transform: translateY(-2px);
    }

    /* About Section */
    .about {
      padding: 5rem 2rem;
      text-align: center;
      background-color: #FFFFFF;
    }

    .about h2 {
      font-size: 2.5rem;
      color: #0077B6;
      margin-bottom: 1.5rem;
    }

    .about p {
      font-size: 1.1rem;
      max-width: 700px;
      margin: 0 auto;
      color: #34495E;
    }

    /* Products Section */
    .products {
      padding: 5rem 2rem;
      text-align: center;
      background-color: #F5FBFF;
    }

    .products h2 {
      font-size: 2.5rem;
      color: #0077B6;
      margin-bottom: 2.5rem;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .product-card {
      background-color: #FFFFFF;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.15);
    }

    .product-card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 1rem;
    }

    .product-card h3 {
      font-size: 1.5rem;
      margin-bottom: 0.75rem;
      color: #023E8A;
    }

    .product-card p {
      font-size: 1.2rem;
      color: #0077B6;
      margin-bottom: 1rem;
    }

    .add-to-cart {
      padding: 0.75rem 1.5rem;
      background-color: #0077B6;
      color: #FFFFFF;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    .add-to-cart:hover {
      background-color: #90E0EF;
      transform: translateY(-2px);
    }

    /* Hydration Tips Section */
    .hydration {
      padding: 5rem 2rem;
      background-color: #FFFFFF;
      text-align: center;
    }

    .hydration h2 {
      font-size: 2.5rem;
      color: #0077B6;
      margin-bottom: 1.5rem;
    }

    .hydration p {
      font-size: 1.1rem;
      margin-bottom: 2.5rem;
      color: #34495E;
    }

    .tips-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .tip-card {
      padding: 1.5rem;
      background-color: #E6F3FA;
      border-radius: 12px;
      transition: transform 0.3s ease;
    }

    .tip-card:hover {
      transform: translateY(-5px);
    }

    .tip-card h3 {
      font-size: 1.4rem;
      margin-bottom: 0.75rem;
      color: #023E8A;
    }

    .tip-card p {
      font-size: 1rem;
      color: #34495E;
    }

    /* Sustainability Section */
    .sustainability {
      padding: 5rem 2rem;
      text-align: center;
      background: linear-gradient(135deg, #90E0EF 0%, #E6F3FA 100%);
    }

    .sustainability h2 {
      font-size: 2.5rem;
      color: #023E8A;
      margin-bottom: 1.5rem;
    }

    .sustainability p {
      font-size: 1.1rem;
      margin-bottom: 2rem;
      max-width: 700px;
      margin: 0 auto;
      color: #34495E;
    }

    .learn-more {
      padding: 1rem 2rem;
      background-color: #0077B6;
      color: #FFFFFF;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    .learn-more:hover {
      background-color: #FFFFFF;
      color: #0077B6;
      transform: translateY(-2px);
    }

    /* Contact Section */
    .contact {
      padding: 5rem 2rem;
      text-align: center;
      background-color: #FFFFFF;
    }

    .contact h2 {
      font-size: 2.5rem;
      color: #0077B6;
      margin-bottom: 1.5rem;
    }

    #contact-form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    #contact-form input,
    #contact-form textarea {
      padding: 1rem;
      border: 1px solid #90E0EF;
      border-radius: 8px;
      font-size: 1rem;
      font-family: 'Montserrat', sans-serif;
      transition: border-color 0.3s ease;
    }

    #contact-form input:focus,
    #contact-form textarea:focus {
      border-color: #0077B6;
      outline: none;
    }

    #contact-form textarea {
      resize: vertical;
      min-height: 120px;
    }

    #contact-form button {
      padding: 1rem;
      background-color: #0077B6;
      color: #FFFFFF;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    #contact-form button:hover {
      background-color: #90E0EF;
      transform: translateY(-2px);
    }

    /* Footer */
    footer {
      padding: 1.5rem;
      text-align: center;
      background-color: #023E8A;
      color: #FFFFFF;
      font-size: 0.9rem;
    }

    /* Responsive Design */
    @media (max-width: 1024px) {
      .hero-content h1 {
        font-size: 2.8rem;
      }

      .hero-content p {
        font-size: 1.1rem;
      }

      .product-grid,
      .tips-grid {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      }
    }

    @media (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 5rem;
        left: 0;
        width: 100%;
        background-color: #FFFFFF;
        padding: 1.5rem;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      .nav-links.active {
        display: flex;
      }

      .nav-links li {
        margin: 0.5rem 0;
      }

      .hamburger {
        display: flex;
      }

      .hero-content h1 {
        font-size: 2rem;
      }

      .hero-content p {
        font-size: 1rem;
      }

      .about h2,
      .products h2,
      .hydration h2,
      .sustainability h2,
      .contact h2 {
        font-size: 2rem;
      }

      #contact-form {
        max-width: 100%;
      }
    }

    @media (max-width: 480px) {
      .hero {
        padding: 1rem;
      }

      .cta-button {
        padding: 0.8rem 1.5rem;
        font-size: 0.9rem;
      }

      .product-card img {
        height: 180px;
      }
    }
  </style>

  <!-- Embedded JavaScript -->
  <script>
    // Hamburger Menu Toggle
    const hamburger = document.querySelector('.hamburger');
    const navLinks = document.querySelector('.nav-links');

    hamburger.addEventListener('click', () => {
      hamburger.classList.toggle('active');
      navLinks.classList.toggle('active');
    });

    // Smooth Scroll for Anchor Links
    document.querySelectorAll('.nav-links a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const section = document.querySelector(this.getAttribute('href'));
        section.scrollIntoView({ behavior: 'smooth' });
        hamburger.classList.remove('active');
        navLinks.classList.remove('active');
      });
    });

    // Add to Cart (Placeholder)
    document.querySelectorAll('.add-to-cart').forEach(button => {
      button.addEventListener('click', () => {
        alert('Added to cart! (Cart functionality to be implemented)');
      });
    });

    // Contact Form Submission
    document.getElementById('contact-form').addEventListener('submit', function(e) {
      e.preventDefault();
      const formData = new FormData(this);
      const data = Object.fromEntries(formData);
      console.log('Form submitted:', data);
      alert('Message sent! (Backend integration needed)');
      this.reset();
    });

    // Learn More Button (Placeholder)
    document.querySelector('.learn-more').addEventListener('click', () => {
      alert('Learn more about our sustainability efforts! (Add detailed page or modal)');
    });
  </script>
</body>
</html>