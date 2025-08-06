<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HawkEye Pool Services</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
  <img src="logo.png" alt="HawkEye Pool Services Logo" class="logo">
  <nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Pool Remodels/Deck Resurfacing</li>
      <li>Pool Repairs</li>
      <li>Installations</li>
      <li>Weekly & Monthly Service Plans</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <img src="images/pool1.jpg" alt="Clean blue pool" width="300">
    <img src="images/pool2.jpg" alt="Pool with waterfall" width="300">
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>HawkEye Pool Services has been keeping pools sparkling for over 5 years. We pride ourselves on reliable, affordable, and friendly service local to Lewisville/Flour mound area.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Phone: <a href="tel:94218435">(123) 456-7890</a></p>
    <p>Email: <a href="mailto:Hawkeyepoolservices@outlook.com">Hawkeyepoolservices@outlook.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 HawkEye Pool Services</p>
  </footer>
</body>
</html>


#css

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

body {
  font-family: 'Montserrat', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #ffffff;
  color: #000;
}

header {
  background: #00a6c7;
  padding: 20px;
  text-align: center;
}

header img.logo {
  max-height: 60px;
  display: block;
  margin: 0 auto 10px;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

/* Accent headings */
h1, h2 {
  color: #00a6c7;
}
