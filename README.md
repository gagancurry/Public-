<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gagan Curry Shop - ガガンのカレー屋さん</title>
  <!-- Google Font: Roboto -->
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #fff;
      color: #333;
      line-height: 1.6;
    }
    /* Header: fixed top, translucent background */
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
      background: url('images/hero_background.jpg') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
      margin-top: 60px; /* Offset fixed header */
    }
    .hero h1 {
      font-size: 3em;
      margin: 0;
    }
    /* Content Sections */
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
    /* Menu Section */
    .menu-section ul {
      list-style: none;
      padding: 0;
      text-align: center;
      margin-bottom: 40px;
    }
    .menu-section ul li {
      margin: 10px 0;
    }
    .menu-section a {
      color: #007BFF;
      text-decoration: none;
      font-weight: 500;
    }
    .menu-section a:hover {
      text-decoration: underline;
    }
    .menu-section img {
      width: 100%;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    /* Footer */
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
    /* Clearfix */
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
      <!-- Replace with your actual logo image path -->
      <img src="images/logo.jpg" alt="Gagan Curry Shop Logo - ガガンのカレー屋さん ロゴ">
    </div>
    <nav>
      <ul>
        <li><a href="#about">About / 概要</a></li>
        <li><a href="#menu">Menu & Photos / メニュー＆写真</a></li>
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
    <h2>About Us / 私たちについて</h2>
    <p>
      Gagan Curry Shop is a specialty restaurant located in Shinagawa, Tokyo, offering authentic Nepalese cuisine and curry.<br>
      ガガンのカレー屋さんは、東京品川に位置する、伝統的なネパール料理とカレーを提供する専門レストランです。
    </p>
  </section>

  <!-- Menu & Photos Section -->
  <section id="menu" class="menu-section">
    <h2>Menu & Photos / メニュー＆写真</h2>
    <p>
  
      .<br>
      UberEatsでメニューの写真をご覧いただくか、下記のリンクをクリックしてその他の写真をご確認ください。
    </p>
    <ul>
      <li>
        <a href="https://www.ubereats.com/store/%E3%82%AB%E3%82%AB%E3%83%B3%E3%81%AE%E3%82%AB%E3%83%AC%E3%83%BC%E5%B1%8B%E3%81%95%E3%82%93%E6%88%B8%E8%B6%8A%E6%94%AF%E5%BA%97/CrmjhNgxXo2oAyyxJ6PoFQ?diningMode=PICKUP" target="_blank">
          View Menu on UberEats (戸越支店) / UberEatsでメニューを見る
        </a>
      </li>
      <li>
        <a href="https://maps.app.goo.gl/2qvRwkFhMhZYhFx66" target="_blank">Restaurant Photo 1 / レストラン写真 1</a>
      </li>
      <li>
        <a href="https://maps.app.goo.gl/XR6vJR7fki7Uu6QK7" target="_blank">Restaurant Photo 2 / レストラン写真 2</a>
      </li>
    </ul>
    <!-- Course Menu Image -->
    <h3>Party & Course Menu / コースメニュー</h3>
    <p>
      Check out our special party courses!<br>
      特別なパーティコースをご覧ください！
    </p>
    <div style="max-width: 500px; margin: 0 auto;">
      <!-- Update with correct path for your course menu image -->
      <img src="images/course_menu.jpg" alt="Party Menu - Gagan Curry Shop / パーティメニュー - ガガンのカレー屋さん">
    </div>
    <h3>Our Offerings / ご提供内容</h3>
    <p>
      <strong>Food Options:</strong> Course, all-you-can-drink (or drinks only), all-you-can-eat, vegetarian menu, vegetable dishes, fish dishes, health & beauty options.<br>
      <strong>料理の選択肢：</strong> コース、飲み放題（またはドリンクのみ）、食べ放題、ベジタリアンメニュー、野菜料理、魚料理、ヘルス＆ビューティーメニューなど。
    </p>
    <p>
      <strong>Drinks:</strong> Sake, shochu, wine, cocktails, etc.<br>
      <strong>ドリンク：</strong> 酒、焼酎、ワイン、カクテルなど。
    </p>
  </section>

  <!-- Location Section -->
  <section id="location">
    <h2>Location & Hours / 住所と営業時間</h2>
    <p>
      Our location: <a href="https://maps.app.goo.gl/QzsSUyWx8cqK5Uko9" target="_blank">View on Map / 地図で見る</a>
    </p>
    <p>
      1 minute walk from Togoshi Station, 3 minutes from Togoshi Ginza Station.<br>
      戸越駅から徒歩1分、戸越銀座駅から徒歩3分。
    </p>
    <p>
      <strong>Business Hours:</strong> 11:00 - 22:30 (Open daily)<br>
      <strong>営業時間：</strong> 11:00～22:30 (毎日営業)
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact & Booking / お問い合わせ & 予約</h2>
    <p>
      <strong>Phone:</strong> 03-6426-7707
    </p>
    <p>
      <strong>Email:</strong> <a href="mailto:gagancurrytogoshi@gmail.com">gagancurrytogoshi@gmail.com</a>
    </p>
    <p>
      <strong>Online Booking:</strong><br>
      <a href="https://tabelog.com/tokyo/A1317/A131712/13291891/" target="_blank">Tabelog</a><br>
      <a href="https://www.hotpepper.jp/strJ004003000/yoyaku/" target="_blank">Hot Pepper</a>
    </p>
    <p>
      <strong>Payment Methods:</strong><br>
      Cards: Master, JCB, AMEX, Diners<br>
      Electronic Money: Suica, Edy, nanaco, WAON, iD, QUICPay<br>
      QR Code Payments: PayPay, d払い, 楽天ペイ, au PAY
    </p>
    <p>
      <strong>Seating:</strong> 32 seats<br>
      <strong>座席：</strong> 32席
    </p>
    <p>
      <strong>Facilities:</strong> Comfortable space, wide seating, power supply available, free Wi-Fi.<br>
      <strong>施設：</strong> 快適な空間、広い座席、電源完備、無料Wi-Fi
    </p>
  </section>

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
