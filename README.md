<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gagan Curry Shop - ガガンのカレー屋さん</title>
  <!-- Google Font: Roboto -->
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #fff;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: rgba(0, 0, 0, 0.7);
      color: #fff;
      padding: 10px 20px;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }
    header .logo img {
      height: 40px;
      vertical-align: middle;
    }
    header nav {
      float: right;
    }
    header nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }
    header nav ul li {
      display: inline-block;
      margin-left: 20px;
      vertical-align: middle;
    }
    header nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 700;
    }

    /* Hero Section */
    .hero {
      background: url('images/gagan_curry_background_final.jpg') no-repeat center center/cover;
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
      display: none; /* Hide text because it's in the background image */
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section h2, section h3 {
      text-align: center;
      margin-bottom: 20px;
    }

    section p {
      margin-bottom: 20px;
      text-align: center;
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

    .clearfix::after {
      content: "";
      clear: both;
      display: table;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header class="clearfix">
    <div class="logo">
      <img src="images/logo.jpg" alt="Gagan Curry Shop Logo - ガガンのカレー屋さん ロゴ">
    </div>
    <nav>
      <ul>
        <li><a href="#about">About / 概要</a></li>
        <li><a href="#menu">Menu / メニュー</a></li>
        <li><a href="#location">Location / 住所</a></li>
        <li><a href="#contact">Contact / お問い合わせ</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Gagan Curry Shop / ガガンのカレー屋さん</h1>
  </section>

  <!-- Other sections remain unchanged -->
  <!-- ... -->

  <!-- Footer Section -->
  <footer>
    <p>
      <a href="https://m.me/113552028518979" target="_blank">Facebook</a> |
      <a href="https://www.instagram.com/gagancurrytogoshi/" target="_blank">Instagram</a>
    </p>
    <p>&copy; 2025 Gagan Curry Shop / ガガンのカレー屋さん. All rights reserved.</p>
  </footer>

</body>
</html>
