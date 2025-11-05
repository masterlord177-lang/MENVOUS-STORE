<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Menvous Store</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: url('a9f353d7c8c4b66978f5e14e787e5fdf.jpg') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 15px 25px;
      background: rgba(0, 0, 0, 0.6);
      backdrop-filter: blur(8px);
    }

    header img {
      height: 45px;
      border-radius: 10px;
    }

    header h1 {
      font-size: 1.4rem;
      font-weight: 600;
      color: #00ff99;
      margin-left: 10px;
    }

    nav {
      display: flex;
      align-items: center;
      gap: 15px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      padding: 8px 15px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 8px;
      transition: 0.3s;
    }

    nav a:hover {
      background: #00ff99;
      color: #000;
    }

    .container {
      padding: 20px;
      max-width: 900px;
      margin: auto;
      background: rgba(0, 0, 0, 0.5);
      border-radius: 12px;
      margin-top: 30px;
    }

    h2 {
      border-left: 5px solid #00ff99;
      padding-left: 10px;
      margin-bottom: 15px;
    }

    .produk-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .produk {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      padding: 15px;
      text-align: center;
      transition: 0.3s;
    }

    .produk:hover {
      transform: translateY(-5px);
      background: rgba(255, 255, 255, 0.2);
    }

    .produk img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }

    .produk h3 {
      margin: 10px 0 5px;
      font-size: 1.1rem;
    }

    .produk p {
      margin-bottom: 8px;
      color: #cfcfcf;
      font-size: 0.9rem;
    }

    .harga {
      font-size: 1rem;
      color: #00ff99;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .produk button {
      background: #00ff99;
      border: none;
      color: #000;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }

    .produk button:hover {
      background: #00cc7a;
    }

    footer {
      text-align: center;
      margin-top: 30px;
      padding: 15px;
      color: #ddd;
      background: rgba(0, 0, 0, 0.6);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <div style="display:flex; align-items:center;">
      <img src="Logo_MENVOUSTORE.png" alt="Logo" />
      <h1>Menvous Store</h1>
    </div>
    <nav>
      <a href="#populer">Populer</a>
      <a href="#roblox">Roblox</a>
      <a href="#premium">Premium</a>
    </nav>
  </header>

  <div class="container" id="populer">
    <h2>⚡ Populer</h2>
    <div class="produk-list">
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=Fish+It+-+Akun" alt="produk1">
        <h3>Fish It - Akun</h3>
        <p>Akun Roblox siap pakai</p>
        <div class="harga">Rp 120.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20Fish%20It%20-%20Akun','_blank')">Beli</button>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=Redfinger" alt="produk2">
        <h3>Redfinger</h3>
        <p>Redeem Code Premium</p>
        <div class="harga">Rp 50.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20Redfinger','_blank')">Beli</button>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=Robux+Manual" alt="produk3">
        <h3>Robux Manual</h3>
        <p>Top-up robux via login</p>
        <div class="harga">Rp 85.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20Robux%20Manual','_blank')">Beli</button>
      </div>
    </div>
  </div>

  <div class="container" id="roblox">
    <h2>🎮 Roblox</h2>
    <div class="produk-list">
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=Fish+It+-+Fish" alt="produk">
        <h3>Fish It - Fish</h3>
        <p>Ikan game Fish It</p>
        <div class="harga">Rp 30.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20Fish%20It%20-%20Fish','_blank')">Beli</button>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=Fish+It+-+Game+Pass" alt="produk">
        <h3>Fish It - Game Pass</h3>
        <p>Game pass Roblox</p>
        <div class="harga">Rp 75.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20Fish%20It%20-%20Game%20Pass','_blank')">Beli</button>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=Fish+It+-+Skin+Rod" alt="produk">
        <h3>Fish It - Skin Rod</h3>
        <p>Skin pancing keren</p>
        <div class="harga">Rp 45.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20Fish%20It%20-%20Skin%20Rod','_blank')">Beli</button>
      </div>
    </div>
  </div>

  <div class="container" id="premium">
    <h2>💎 Premium</h2>
    <div class="produk-list">
      <div class="produk">
        <img src="https://via.placeholder.com/300x150?text=VIP+Access" alt="produk">
        <h3>VIP Access</h3>
        <p>Akses premium semua fitur</p>
        <div class="harga">Rp 150.000</div>
        <button onclick="window.open('https://wa.me/6282364492977?text=Halo%20saya%20ingin%20beli%20VIP%20Access','_blank')">Beli</button>
      </div>
    </div>
  </div>

  <footer>
    © 2025 Menvous Store. All rights reserved.
  </footer>
</body>
</html>
