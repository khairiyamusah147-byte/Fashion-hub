index.html and paste this:
HTML
<!DOCTYPE html>
<html>
<head>
  <title>Client Business Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Elite Beauty Salon</h1>
  <p>We make you look beautiful and confident</p>
</header>

<section class="services">
  <h2>Our Services</h2>
  <p>Hair Styling • Makeup • Nails • Spa</p>
</section>

<section class="about">
  <h2>About Us</h2>
  <p>We are a professional salon offering quality beauty services.</p>
</section>

<section class="contact">
  <h2>Contact Us</h2>
  <button onclick="contact()">Click to Book</button>
  <p id="msg"></p>
</section>

<script src="script.js"></script>
</body>
</html>
