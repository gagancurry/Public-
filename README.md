<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gagan Curry Shop - ガガンのカレー屋さん</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700&display=swap" rel="stylesheet"/>
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #fff;
      color: #333;
      line-height: 1.6;
      scroll-behavior: smooth; /* Added for smooth scrolling */
    }

    header {
      background: rgba(0, 0, 0, 0.8);
      color: #fff;
      padding: 10px 20px;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header .logo img {
      height: 40px;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
    }

    nav ul li {
      margin-left: 20px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 700;
    }

    .hero {
      background: url("IMG_0322.JPG") no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
      margin-top: 60px;
    }

    .hero h1 {
      font-size: 3em;
      margin: 0;
      background: rgba(0, 0, 0, 0.5);
      padding: 20px;
      border-radius: 10px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    footer a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="images/logo.jpg" alt="Gagan Curry Shop Logo" />
    </div>
    <nav>
      <ul>
        <li><a href="#about">About / 概要</a></li>
        <li><a href="#menu">Menu / メニュー</a></li> <!-- Link to Menu Section -->
        <li><a href="#location">Location / 住所</a></li>
        <li><a href="#contact">Contact / お問い合わせ</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Gagan Curry Shop / ガガンのカレー屋さん</h1>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Us / 概要</h2>
    <p>Welcome to Gagan Curry Shop, where we serve the most authentic and flavorful curries, made with fresh, high-quality ingredients!</p>
    <p>Our mission is to bring the authentic taste of Nepali and Indian curries to Togoshi, Tokyo, and offer an unforgettable dining experience!</p>
  </section>

  <!-- Menu Section -->
  <section id="menu">
    <h2>Our Menu / メニュー</h2>
    <p>Explore our wide variety of delicious curries and sides, all made with fresh ingredients and traditional recipes!</p>
    
    <div>
      <h3>Curries</h3>
      <ul>
        <li>Butter Chicken Curry - ¥1000</li>
        <li>Dal Curry - ¥800</li>
        <li>Vegetable Curry - ¥900</li>
        <li>Chicken Tikka Masala - ¥1200</li>
      </ul>
    </div>

    <div>
      <h3>Breads</h3>
      <ul>
        <li>Cheese Naan - ¥400</li>
        <li>Garlic Naan - ¥350</li>
        <li>Plain Naan - ¥300</li>
        <li>Roti - ¥250</li>
      </ul>
    </div>

    <div>
      <h3>Side Dishes</h3>
      <ul>
        <li>Samosa (2 pieces) - ¥500</li>
        <li>Raita - ¥200</li>
        <li>Papadam - ¥150</li>
      </ul>
    </div>

    <div>
      <h3>Drinks</h3>
      <ul>
        <li>Lassi (Mango) - ¥350</li>
        <li>Soft Drink - ¥200</li>
        <li>Masala Chai - ¥250</li>
      </ul>
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 Gagan Curry Shop / ガガンのカレー屋さん. All rights reserved.</p>
  </footer>

</body>
</html>
