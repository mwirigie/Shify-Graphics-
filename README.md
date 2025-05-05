<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Shify Graphics</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f7f7f7;
      color: #333;
    }
    header {
      background: #111;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    section {
      padding: 20px;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .services, .about, .process {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 15px;
    }
    .card {
      background: white;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      width: 280px;
      text-align: center;
    }
    form input, form textarea {
      width: 100%;
      padding: 8px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .btn {
      background: #111;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .whatsapp-btn {
      display: inline-block;
      background: #25d366;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      border-radius: 5px;
      text-decoration: none;
    }
  </style>
</head>
<body>

<header>
  <h1>Shify Graphics</h1>
  <p>Creative Graphic Design Solutions</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#about">About Us</a>
  <a href="#process">How We Work</a>
  <a href="#contact">Contact</a>
</nav>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">Logo Design</div>
    <div class="card">Poster Design</div>
    <div class="card">Flyer Design</div>
    <div class="card">Business Card Design</div>
    <div class="card">Brochure Design</div>
    <div class="card">Social Media Graphics</div>
    <div class="card">Brand Identity Development</div>
    <div class="card">Infographic Design</div>
  </div>
</section>

<section id="about">
  <h2>About Us</h2>
  <p style="text-align:center;">
    At Shify Graphics, we specialize in creating unique and impactful designs that help brands communicate their story. With years of experience in the graphic design industry, we provide creative solutions tailored to your business needs. Whether you need a new logo, marketing materials, or a complete brand overhaul, we’re here to help.
  </p>
</section>

<section id="process">
  <h2>How We Work</h2>
  <div class="process">
    <div class="card">
      <h3>1. Initial Consultation</h3>
      <p>We begin by understanding your business and design needs to create a roadmap for the project.</p>
    </div>
    <div class="card">
      <h3>2. Concept Development</h3>
      <p>We design multiple concepts based on your input and feedback, refining the design until it's perfect.</p>
    </div>
    <div class="card">
      <h3>3. Final Design</h3>
      <p>Once you approve a design, we finalize all deliverables and ensure you have everything you need.</p>
    </div>
  </div>
</section>

<section id="testimonials">
  <h2>Testimonials</h2>
  <p style="text-align:center;">"Shify Graphics gave our business a stunning look!" — Happy Client</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form action="https://formspree.io/f/yourFormID" method="POST">
    <input type="text" name="name" placeholder="Your Name" required />
    <input type="email" name="email" placeholder="Your Email" required />
    <textarea name="message" placeholder="Your Message" required></textarea>
    <button type="submit" class="btn">Send</button>
  </form>
  <a class="whatsapp-btn" href="https://wa.me/254703865628" target="_blank">
    Chat on WhatsApp
  </a>
</section>

</body>
</html>
