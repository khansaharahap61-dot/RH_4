<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RH Market – Jual Beli Mudah & Aman</title>
  <link href="https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', Arial, sans-serif;
      background: #f4f6f8;
      color: #222;
    }
    header {
      background: linear-gradient(90deg, #08aeea 0%, #2af598 100%);
      color: #fff;
      padding: 32px 0 24px 0;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    }
    header h1 {
      margin: 0 0 8px 0;
      font-size: 2.5em;
      letter-spacing: 1px;
    }
    header p {
      margin: 0;
      font-size: 1.2em;
      letter-spacing: 0.5px;
    }
    .products-section {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 28px;
    }
    .product-card {
      background: #fff;
      border-radius: 18px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.08);
      overflow: hidden;
      transition: transform 0.2s;
      display: flex;
      flex-direction: column;
    }
    .product-card:hover {
      transform: translateY(-8px) scale(1.03);
      box-shadow: 0 12px 28px rgba(0,0,0,0.12);
    }
    .product-card img {
      width: 100%;
      aspect-ratio: 1 / 1;
      object-fit: cover;
      background: #e3e3e3;
    }
    .product-info {
      flex: 1;
      padding: 20px 16px 16px 16px;
      display: flex;
      flex-direction: column;
    }
    .product-info h3 {
      margin: 0 0 10px 0;
      font-size: 1.15em;
      font-weight: 700;
      color: #08aeea;
    }
    .product-info p {
      flex: 1;
      margin: 0 0 8px 0;
      font-size: 1em;
      color: #333;
    }
    .price {
      font-weight: bold;
      color: #2af598;
      margin-bottom: 10px;
      font-size: 1.1em;
    }
    .buy-btn {
      background: linear-gradient(90deg, #08aeea 0%, #2af598 100%);
      color: #fff;
      border: none;
      border-radius: 6px;
      padding: 10px 0;
      font-size: 1em;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.2s;
      box-shadow: 0 2px 8px rgba(8,174,234,0.12);
    }
    .buy-btn:hover {
      background: linear-gradient(90deg, #2af598 0%, #08aeea 100%);
    }
    footer {
      background: #1e293b;
      color: #fff;
      padding: 20px 0;
      text-align: center;
      margin-top: 50px;
      font-size: 0.95em;
      letter-spacing: 0.5px;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 1.6em; }
      .products-section { margin: 24px auto; padding: 0 8px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>RH Market</h1>
    <p>Tempat jual beli barang & jasa terbaik. Transaksi aman, cepat, dan mudah!</p>
  </header>
  <section class="products-section">
    <div class="products-grid">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Headphone Wireless">
        <div class="product-info">
          <h3>Headphone Wireless</h3>
          <p>Suara jernih, baterai tahan lama. Cocok untuk gaming & musik.</p>
          <div class="price">Rp350.000</div>
          <button class="buy-btn" onclick="beli('Headphone Wireless')">Beli</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1519985176271-adb1088fa94c?auto=format&fit=crop&w=400&q=80" alt="Jasa Desain Logo">
        <div class="product-info">
          <h3>Jasa Desain Logo</h3>
          <p>Paket desain profesional untuk bisnis UMKM & startup Anda.</p>
          <div class="price">Rp150.000</div>
          <button class="buy-btn" onclick="beli('Jasa Desain Logo')">Beli</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1503602642458-232111445657?auto=format&fit=crop&w=400&q=80" alt="Jam Tangan Pria">
        <div class="product-info">
          <h3>Jam Tangan Pria</h3>
          <p>Model elegan & tahan air, cocok untuk segala aktivitas.</p>
          <div class="price">Rp220.000</div>
          <button class="buy-btn" onclick="beli('Jam Tangan Pria')">Beli</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" alt="Sepatu Sneakers">
        <div class="product-info">
          <h3>Sepatu Sneakers</h3>
          <p>Nyaman dipakai seharian, cocok untuk anak muda & dewasa.</p>
          <div class="price">Rp400.000</div>
          <button class="buy-btn" onclick="beli('Sepatu Sneakers')">Beli</button>
        </div>
      </div>
    </div>
  </section>
  <footer>
    &copy; 2025 RH Market. Powered by khansaharahap61-dot.
  </footer>
  <script>
    function beli(namaProduk) {
      alert("Terima kasih telah membeli " + namaProduk + "!\nSilakan lanjutkan pembayaran melalui chat admin.");
    }
  </script>
</body>
</html>
