<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LUXURY CARS — Каталог премиальных автомобилей</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #0d0d0d;
    color: #f0f0f0;
  }
  header {
    background: linear-gradient(135deg, #1a1a1a, #000);
    padding: 30px 20px;
    text-align: center;
    border-bottom: 2px solid #c9a227;
  }
  header h1 {
    font-size: 2.2em;
    letter-spacing: 4px;
    color: #c9a227;
    text-transform: uppercase;
  }
  header p { color: #999; margin-top: 8px; letter-spacing: 1px; }

  .catalog {
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 30px;
  }
  .car-card {
    background: #161616;
    border: 1px solid #2a2a2a;
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.3s, border-color 0.3s;
  }
  .car-card:hover {
    transform: translateY(-6px);
    border-color: #c9a227;
  }
  .car-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
  }
  .car-info { padding: 20px; }
  .car-info h2 {
    font-size: 1.3em;
    margin-bottom: 6px;
    color: #fff;
  }
  .car-info .brand {
    color: #c9a227;
    font-size: 0.85em;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-bottom: 10px;
  }
  .car-info .specs {
    color: #888;
    font-size: 0.9em;
    margin-bottom: 15px;
    line-height: 1.6;
  }
  .price {
    font-size: 1.5em;
    font-weight: bold;
    color: #c9a227;
  }
  .price small { font-size: 0.5em; color: #777; font-weight: normal; }

  footer {
    text-align: center;
    padding: 30px;
    color: #555;
    border-top: 1px solid #222;
    margin-top: 40px;
    font-size: 0.9em;
  }
</style>
</head>
<body>

<header>
  <h1>Luxury Cars</h1>
  <p>Каталог премиальных автомобилей</p>
</header>

<div class="catalog">

  <div class="car-card">
    <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=600" alt="Porsche 911">
    <div class="car-info">
      <p class="brand">Porsche</p>
      <h2>911 Turbo S</h2>
      <p class="specs">3.8 л • 650 л.с. • 0–100 за 2.7 с • Полный привод</p>
      <p class="price">24 500 000 ₽</p>
    </div>
  </div>

  <div class="car-card">
    <img src="https://images.unsplash.com/photo-1555215695-3004980ad54e?w=600" alt="BMW M5">
    <div class="car-info">
      <p class="brand">BMW</p>
      <h2>M5 Competition</h2>
      <p class="specs">4.4 л V8 • 625 л.с. • 0–100 за 3.3 с • Полный привод</p>
      <p class="price">14 900 000 ₽</p>
    </div>
  </div>

  <div class="car-card">
    <img src="https://images.unsplash.com/photo-1618843479313-40f8afb4b4d8?w=600" alt="Mercedes">
    <div class="car-info">
      <p class="brand">Mercedes-Benz</p>
      <h2>AMG GT 63 S</h2>
      <p class="specs">4.0 л V8 • 639 л.с. • 0–100 за 3.2 с • Полный привод</p>
      <p class="price">18 700 000 ₽</p>
    </div>
  </div>

  <div class="car-card">
    <img src="https://images.unsplash.com/photo-1592198084033-aade902d1aae?w=600" alt="Lamborghini">
    <div class="car-info">
      <p class="brand">Lamborghini</p>
      <h2>Huracán EVO</h2>
      <p class="specs">5.2 л V10 • 640 л.с. • 0–100 за 2.9 с • Полный привод</p>
      <p class="price">32 000 000 ₽</p>
    </div>
  </div>

  <div class="car-card">
    <img src="https://images.unsplash.com/photo-1583121274602-3e2820c69888?w=600" alt="Ferrari">
    <div class="car-info">
      <p class="brand">Ferrari</p>
      <h2>F8 Tributo</h2>
      <p class="specs">3.9 л V8 • 720 л.с. • 0–100 за 2.9 с • Задний привод</p>
      <p class="price">35 500 000 ₽</p>
    </div>
  </div>

  <div class="car-card">
    <img src="https://images.unsplash.com/photo-1606664515524-ed2f786a0bd6?w=600" alt="Rolls-Royce">
    <div class="car-info">
      <p class="brand">Rolls-Royce</p>
      <h2>Ghost</h2>
      <p class="specs">6.75 л V12 • 571 л.с. • Максимальный комфорт • Полный привод</p>
      <p class="price">48 000 000 ₽</p>
    </div>
  </div>

</div>

<footer>
  © 2026 Luxury Cars — учебный проект. Цены условные.
</footer>

</body>
</html>
