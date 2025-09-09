<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Catchhub</title>
  <link rel="icon" type="image/jpg" href="favicon.jpg">
  <style>
  
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: #333;
      background: #fff;
      line-height: 1.6;
    }

   
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      background: #f9f9f9;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .logo {
      height: 50px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

  
    .hero {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 60px 50px;
      background: linear-gradient(to right, #6dd5ed, #2193b0);
      color: #fff;
    }

    .hero-text {
      max-width: 50%;
    }

    .hero-text h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .hero-text .buttons img {
      height: 50px;
      margin-right: 10px;
    }

    .hero-image img {
      max-width: 350px;
      border-radius: 20px;
    }


    .features {
      padding: 50px;
      text-align: center;
    }

    .features h2 {
      margin-bottom: 30px;
      font-size: 2rem;
    }

    .feature-items {
      display: flex;
      justify-content: center;
      gap: 40px;
    }

    .feature {
      width: 250px;
    }

    .feature img {
      height: 60px;
      margin-bottom: 15px;
    }

    .feature h3 {
      margin-bottom: 10px;
    }

  
    .screenshots {
      padding: 50px;
      text-align: center;
      background: #f9f9f9;
    }

    .screenshots h2 {
      margin-bottom: 30px;
      font-size: 2rem;
    }

    .screens {
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    .screens img {
      max-width: 200px;
      border-radius: 10px;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Catchhub Logo" class="logo">
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Screenshots</a></li>
        <li><a href="#">Download</a></li>
      </ul>
    </nav>
  </header>
  <section class="hero">
    <div class="hero-text">
      <h1>Welcome to Catchhub</h1>
      <p>Your ultimate app for everything.</p>
      <div class="buttons">
        <a href="#"><img src="play_store.png" alt="Play Store"></a>
        <a href="#"><img src="app_store.png" alt="App Store"></a>
      </div>
    </div>
    <div class="hero-image">
      <img src="top_screens.png" alt="App Preview">
    </div>
  </section>

  <!-- Features Section -->
  <section class="features">
    <h2>Amazing Features</h2>
    <div class="feature-items">
      <div class="feature">
        <img src="vectors.png" alt="Feature Icon">
        <h3>Fast</h3>
        <p>Enjoy super fast performance with Catchhub.</p>
      </div>
      <div class="feature">
        <img src="vectors.png" alt="Feature Icon">
        <h3>Secure</h3>
        <p>Your data is always protected with Catchhub.</p>
      </div>
      <div class="feature">
        <img src="vectors.png" alt="Feature Icon">
        <h3>User Friendly</h3>
        <p>Easy to use with a clean and modern interface.</p>
      </div>
    </div>
  </section>


  <section class="screenshots">
    <h2>App Screenshots</h2>
    <div class="screens">
      <img src="sec_screens.png" alt="Screenshot 1">
      <img src="thhh_screens.png" alt="Screenshot 2">
      <img src="for_screens.png" alt="Screenshot 3">
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Catchhub. All rights reserved.</p>
  </footer>
</body>
</html>
