<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Daftar Menu Makanan</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fafafa;
    }
    header {
      background: #ff7043;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }
    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 20px;
    }
    .menu-item {
      background: white;
      padding: 16px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      margin-bottom: 20px;
      display: flex;
      gap: 20px;
      align-items: center;
    }
    .menu-item img {
      width: 120px;
      height: 120px;
      object-fit: cover;
      border-radius: 10px;
    }
    .menu-info h3 {
      margin: 0;
      font-size: 22px;
      color: #333;
    }
    .menu-info p {
      margin: 6px 0;
      color: #666;
    }
    .price {
      font-weight: bold;
      color: #e64a19;
      margin-top: 4px;
    }
  </style>
</head>
<body>
  <header>Daftar Menu Makanan</header>

  <div class="container">

    <div class="menu-item">
      <img src="https://via.placeholder.com/120" alt="Klepon" />
      <div class="menu-info">
        <h3>Klepon</h3>
        <p>Kue tradisional berisi gula merah dan taburan kelapa.</p>
        <div class="price">Rp 3.000</div>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://via.placeholder.com/120" alt="Es Dawet" />
      <div class="menu-info">
        <h3>Es Dawet</h3>
        <p>Minuman segar cendol dengan santan dan gula merah.</p>
        <div class="price">Rp 5.000</div>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://via.placeholder.com/120" alt="Es Gempol" />
      <div class="menu-info">
        <h3>Es Gempol</h3>
        <p>Minuman tradisional dengan gempol tepung beras dan kuah santan manis.</p>
        <div class="price">Rp 7.000</div>
      </div>
    </div>

    <div class="menu-item">
      <img src="https://via.placeholder.com/120" alt="Nasi Soto" />
      <div class="menu-info">
        <h3>Nasi Soto</h3>
        <p>Soto kuah hangat dengan nasi dan topping khas.</p>
        <div class="price">Rp 8.000</div>
      </div>
    </div>

  </div>
</body>
</html>
