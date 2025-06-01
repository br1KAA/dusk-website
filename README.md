<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DUSK ESports</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Orbitron', sans-serif; margin: 0; background: #0b0f1a; color: white; }
    header { display: flex; justify-content: space-between; align-items: center; padding: 1em 2em; background: #111; }
    header img { height: 60px; }
    nav a { color: white; margin: 0 1em; text-decoration: none; }
    .hero { background: url('https://via.placeholder.com/1600x600') center/cover no-repeat; padding: 4em 2em; text-align: center; }
    .hero h1 { font-size: 3em; }
    .hero button { padding: 0.8em 1.5em; background: #1e90ff; border: none; font-size: 1em; cursor: pointer; }
    section { padding: 2em; max-width: 1000px; margin: auto; }
    .roster, .matches, .media-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1em; }
    .card { background: #1a1a2e; padding: 1em; border-radius: 8px; text-align: center; }
    .media-gallery img { width: 100%; border-radius: 8px; }
    .footer { background: #111; padding: 2em; text-align: center; }
    .social-icons img { height: 30px; margin: 0 0.5em; }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <img src="final.png" alt="DUSK Logo" />
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#team">Team</a>
      <a href="#matches">Matches</a>
      <a href="#media">Media</a>
      <a href="#news">News</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Shadows rise at dusk</h1>
    <button>Join Discord</button>
    <button>Watch Stream</button>
  </section>

  <!-- About Us -->
  <section id="about">
    <h2>About Us</h2>
    <p>The iconic motif of a lynx figure in this logo is not only appealing but also symbolizes intelligence, sharpness, and speed – qualities that are of great importance in the world of gaming and esports. The lynx stands for agility in strategy and precision in movement, perfectly summarizing what DUSK ESports represents.</p>
    <p><strong>Founded:</strong> May 2025</p>
    <p><strong>Player Locations:</strong> 🇩🇪 🇷🇸</p>
    <p><strong>Team Goals:</strong> Become a real e-sports team</p>
  </section>

  <!-- Team Roster -->
  <section id="team">
    <h2>Team Roster</h2>
    <div class="roster">
      <div class="card">Requiem 🇩🇪<br>AWPer<br><a href="https://www.faceit.com/en/players/DUSK_Requiem">Faceit</a></div>
      <div class="card">st4rk 🇩🇪<br>Entry Fragger / IGL<br><a href="https://www.faceit.com/en/players/vayct">Faceit</a></div>
      <div class="card">OGFireflyracoon 🇩🇪<br>Support<br><a href="https://www.faceit.com/en/players/Fireflyrcoon">Faceit</a></div>
      <div class="card">Bandit 🇩🇪<br>2nd Entry<br><a href="https://www.faceit.com/en/players/MorningCraft">Faceit</a></div>
      <div class="card">TAGLIATELLE DI CARNE 🇩🇪<br>Lurker<br><a href="#">Faceit</a></div>
      <div class="card">br1KAA 🇷🇸<br>Coach<br><a href="https://www.faceit.com/en/players/br1KAA">Faceit</a></div>
    </div>
  </section>

  <!-- Matches & Results -->
  <section id="matches">
    <h2>Matches & Results</h2>
    <ul>
      <li>May 30, 2025 - DUSK vs Team A - Win 16:12</li>
      <li>May 28, 2025 - DUSK vs Team B - Loss 13:16</li>
      <li>May 25, 2025 - DUSK vs Team C - Win 16:8</li>
    </ul>
    <button>View all matches</button>
  </section>

  <!-- Media -->
  <section id="media">
    <h2>Media</h2>
    <iframe width="100%" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
    <div class="media-gallery">
      <img src="https://via.placeholder.com/300x200" alt="Gallery image 1">
      <img src="https://via.placeholder.com/300x200" alt="Gallery image 2">
      <img src="https://via.placeholder.com/300x200" alt="Gallery image 3">
      <img src="https://via.placeholder.com/300x200" alt="Gallery image 4">
    </div>
    <button>Twitch Channel</button>
    <button>YouTube Channel</button>
  </section>

  <!-- News / Blog -->
  <section id="news">
    <h2>News</h2>
    <div>
      <h3>Team DUSK qualifies for playoffs</h3>
      <p>After an intense series of matches, DUSK moves forward. – May 31, 2025</p>
      <h3>New lineup announced!</h3>
      <p>Meet our newest players joining the ranks. – May 20, 2025</p>
      <h3>Our first win!</h3>
      <p>DUSK ESports claims their first victory. – May 15, 2025</p>
    </div>
    <button>All news</button>
  </section>

  <!-- Sponsors -->
  <section>
    <h2>Our Sponsors</h2>
    <img src="https://via.placeholder.com/150x50" alt="Sponsor 1">
    <img src="https://via.placeholder.com/150x50" alt="Sponsor 2">
  </section>

  <!-- Footer -->
  <footer class="footer" id="contact">
    <p>Contact: contact@duskesports.gg</p>
    <div class="social-icons">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Twitter" />
      <img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram" />
      <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" alt="YouTube" />
    </div>
    <p>&copy; 2025 DUSK ESports. All rights reserved.</p>
  </footer>
</body>
</html>
