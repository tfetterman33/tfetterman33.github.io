# tfetterman33.github.io
echo "# Business" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tfetterman33/Business.git
git push -u origin main
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tim Fetterman - Digital Marketing Agency</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <header>
    <nav>
      <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <div class="hero-content">
      <h1>Welcome to Tim Fetterman</h1>
      <p>Your trusted partner for digital marketing success</p>
      <a href="#contact" class="btn">Get Started</a>
    </div>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="service">
      <img src="service1.jpg" alt="Service 1">
      <h3>Search Engine Optimization</h3>
      <p>We optimize your website to improve its visibility on search engines and drive organic traffic.</p>
    </div>
    <div class="service">
      <img src="service2.jpg" alt="Service 2">
      <h3>Social Media Marketing</h3>
      <p>We create effective social media campaigns to engage your audience and boost brand awareness.</p>
    </div>
    <div class="service">
      <img src="service3.jpg" alt="Service 3">
      <h3>Pay-Per-Click Advertising</h3>
      <p>We run targeted PPC campaigns to drive instant traffic and maximize your return on investment.</p>
    </div>
  </section>

  <section id="portfolio">
    <h2>Our Portfolio</h2>
    <div class="portfolio-item">
      <img src="portfolio1.jpg" alt="Portfolio 1">
      <h3>Client Project 1</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris accumsan volutpat lectus, nec bibendum nisl.</p>
    </div>
    <div class="portfolio-item">
      <img src="portfolio2.jpg" alt="Portfolio 2">
      <h3>Client Project 2</h3>
      <p>Integer in fermentum lectus, ut sodales ex. Vivamus aliquet auctor commodo.</p>
    </div>
    <div class="portfolio-item">
      <img src="portfolio3.jpg" alt="Portfolio 3">
      <h3>Client Project 3</h3>
      <p>Praesent pellentesque auctor tellus, eget accumsan tortor congue vel.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <textarea placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2023 Tim Fetterman. All rights reserved.</p>
  </footer>
</body>

</html>
