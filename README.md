<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="SerèneSource - Premium Spring Water from Pristine Sources">
  <title>SerèneSource - Premium Spring Water</title>
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
      font-family: 'Arial', sans-serif;
      color: #023E8A;
      background-color: #E6F3FA;
      line-height: 1.6;
    }

    /* Navigation */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background-color: #FFFFFF;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .logo-img {
      height: 50px;
    }

    .nav-links {
      display: flex;
      list-style: none;
    }

    .nav-links li {
      margin-left: 20px;
    }

    .nav-links a {
      text-decoration: none;
      color: #0077B6;
      font-weight: bold;
    }

    .nav-links a:hover {
      color: #90E0EF;
    }

    .hamburger {
      display: none;
      flex-direction: column;
      cursor: pointer;
    }

    .hamburger span {
      width: 25px;
      height: 3px;
      background-color: #0077B6;
      margin: 2px 0;
    }

    /* Hero Section */
    .hero {
      height: 80vh;
      background: url('assets/hero-bg.jpg') no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #FFFFFF;
    }

    .hero-content h1 {
      font-size: 48px;
      margin-bottom: 20px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }

    .hero-content p {
      font-size: 20px;
      margin-bottom: 30px;
    }

    .cta-button {
      padding: 15px 30px;
      background-color: #0077B6;
      color: #FFFFFF;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    .cta-button:hover {
      background-color: #90E0EF;
    }

    /* About Section */
    .about {
      padding: 60px 20px;
      text-align: center;
      background-color: #FFFFFF;
    }

    .about h2 {
      font-size: 36px;
      color: #0077B6;
      margin-bottom: 20px;
    }

    .about p {
      font-size: 18px;
      max-width: 800px;
      margin: 0 auto;
    }

    /* Products Section */
    .products {
      padding: 60px 20px;
      text-align: center;
    }

    .products h2 {
      font-size: 36px;
      color: #0077B6;
      margin-bottom: 40px;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .product-card {
      background-color: #FFFFFF;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }

    .product-card:hover {
      transform: translateY(-5px);
    }

    .product-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .product-card h3 {
      font-size: 24px;
      margin-bottom: 10px;
    }

    .product-card p {
      font-size: 18px;
      color: #0077B6;
      margin-bottom: 15px;
    }

    .add-to-cart {
      padding: 10px 20px;
      background-color: #0077B6;
      color: #FFFFFF;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .add-to-cart:hover {
      background-color: #90E0EF;
    }

    /* Hydration Tips Section */
    .hydration {
      padding: 60px 20px;
      background-color: #FFFFFF;
      text-align: center;
    }

    .hydration h2 {
      font-size: 36px;
      color: #0077B6;
      margin-bottom: 20px;
    }

    .hydration p {
      font-size: 18px;
      margin-bottom: 40px;
    }

    .tips-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .tip-card {
      padding: 20px;
      background-color: #E6F3FA;
      border-radius: 10px;
    }

    .tip-card h3 {
      font-size: 22px;
      margin-bottom: 10px;
    }

    .tip-card p {
      font-size: 16px;
    }

    /* Sustainability Section */
    .sustainability {
      padding: 60px 20px;
      text-align: center;
      background-color: #90E0EF;
    }

    .sustainability h2 {
      font-size: 36px;
      color: #023E8A;
      margin-bottom: 20px;
    }

    .sustainability p {
      font-size: 18px;
      margin-bottom: 30px;
      max-width: 800px;
      margin: 0 auto;
    }

    .learn-more {
      padding: 15px 30px;
      background-color: #0077B6;
      color: #FFFFFF;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .learn-more:hover {
      background-color: #FFFFFF;
      color: #0077B6;
    }

    /* Contact Section */
    .contact {
      padding: 60px 20px;
      text-align: center;
    }

    .contact h2 {
      font-size: 36px;
      color: #0077B6;
      margin-bottom: 20px;
    }

    #contact-form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    #contact-form input,
    #contact-form textarea {
      padding: 15px;
      border: 1px solid #90E0EF;
      border-radius: 5px;
      font-size: 16px;
    }

    #contact-form textarea {
      resize: vertical;
      min-height: 150px;
    }

    #contact-form button {
      padding: 15px;
      background-color: #0077B6;
      color: #FFFFFF;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    #contact-form button:hover {
      background-color: #90E0EF;
    }

    /* Footer */
    footer {
      padding: 20px;
      text-align: center;
      background-color: #023E8A;
      color: #FFFFFF;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 70px;
        left: 0;
        width: 100%;
        background-color: #FFFFFF;
        padding: 20px;
      }

      .nav-links.active {
        display: flex;
      }

      .hamburger {
        display: flex;
      }

      .hero-content h1 {
        font-size: 32px;
      }

      .hero-content p {
        font-size: 16px;
      }

      .product-grid,
      .tips-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <!-- Embedded JavaScript -->
  <script>
    // Hamburger Menu Toggle
    const hamburger = document.querySelector('.hamburger');
    const navLinks = document.querySelector('.nav-links');

    hamburger.addEventListener('click', () => {
      navLinks.classList.toggle('active');
    });

    // Smooth Scroll for Anchor Links
    document.querySelectorAll('.nav-links a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const section = document.querySelector(this.getAttribute('href'));
        section.scrollIntoView({ behavior: 'smooth' });
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