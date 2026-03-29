<!DOCTYPE html>
<html>
<head>
  <title>Chandan Decorators</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    body {
      font-family: Arial;
      margin: 0;
      background-color: #f5f5f5;
    }

    header {
      background: linear-gradient(to right, #d62828, #f77f00);
      color: white;
      padding: 30px;
      text-align: center;
    }

    nav {
      background: #222;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 30px;
      text-align: center;
    }

    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background: white;
      margin: 15px;
      padding: 20px;
      width: 250px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .gallery img {
      width: 250px;
      margin: 10px;
      border-radius: 10px;
    }

    .btn {
      display: inline-block;
      padding: 12px 20px;
      background: green;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      margin-top: 10px;
    }

    footer {
      background: #111;
      color: white;
      padding: 15px;
      text-align: center;
    }
  </style>
</head>

<body>

<header>
  <h1>Chandan Decorators 🎉</h1>
  <p>By Chandan Kumar | Wedding & Event Specialist</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#services">Services</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
</nav>

<section>
  <h2>Welcome</h2>
  <p>We make your events beautiful and memorable ✨</p>
  <a class="btn" href="https://wa.me/918210264657">📲 Book on WhatsApp</a>
</section>

<section id="services">
  <h2>Our Services</h2>

  <div class="services">

    <div class="card">
      <h3>Wedding Decoration 💍</h3>
      <p>Stage, mandap, and full venue decoration</p>
    </div>

    <div class="card">
      <h3>Birthday Decoration 🎂</h3>
      <p>Balloon, theme and kids party decoration</p>
    </div>

    <div class="card">
      <h3>Event Decoration 🎊</h3>
      <p>All types of parties and functions</p>
    </div>

  </div>
</section>

<section id="gallery">
  <h2>Our Work</h2>

  <div class="gallery">
    <img src="https://via.placeholder.com/250" alt="Decoration">
    <img src="https://via.placeholder.com/250" alt="Decoration">
    <img src="https://via.placeholder.com/250" alt="Decoration">
  </div>

</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>📞 Phone: 8210264657</p>
  <p>📍 Location: Jamtara</p>

  <a class="btn" href="https://wa.me/918210264657">Chat on WhatsApp</a>
</section>

<footer>
  <p>© 2026 Chandan Decorators | Designed by Chandan Kumar</p>
</footer>

</body>
</html>