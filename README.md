# RH_4
menghubungkan penjual dengan pembeli barang dan jasa
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Toko Online Sederhana</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: teal;
      color: white;
      padding: 15px;
      text-align: center;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      transition: 0.3s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      border-radius: 10px;
    }
    .product h3 {
      margin: 10px 0;
    }
    .product button {
      padding: 10px 15px;
      background: teal;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .product button:hover {
      background: darkcyan;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #333;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>🛒 Toko Online Sederhana</h1>
    <p>Belanja mudah, cepat, dan terpercaya</p>
  </header>

  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Produk 1">
      <h3>Produk 1</h3>
      <p>Rp50.000</p>
      <button onclick="beli('Produk 1')">Beli Sekarang</button>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Produk 2">
      <h3>Produk 2</h3>
      <p>Rp75.000</p>
      <button onclick="beli('Produk 2')">Beli Sekarang</button>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Produk 3">
      <h3>Produk 3</h3>
      <p>Rp100.000</p>
      <button onclick="beli('Produk 3')">Beli Sekarang</button>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Toko Online Sederhana. All Rights Reserved.</p>
  </footer>

  <script>
    function beli(namaProduk) {
      alert("Kamu membeli " + namaProduk + " ✅");
    }
  </script>

</body>
</html>
