# Noche-Sobrenatural-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Noche Sobrenatural - Entradas</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/qrious@4.0.2/dist/qrious.min.js"></script>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #000;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background: linear-gradient(90deg, #ff0000, #6a00ff);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }
    .tickets {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .ticket {
      background-color: #111;
      border: 2px solid #ff0000;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
    }
    .ticket h2 {
      margin-top: 0;
      font-size: 1.8rem;
      color: #ff4444;
    }
    .price {
      font-size: 1.5rem;
      font-weight: bold;
      margin: 10px 0;
      color: #00ffea;
    }
    .details {
      font-size: 0.95rem;
      margin-bottom: 15px;
    }
    canvas {
      margin: 10px auto;
      display: block;
      border: 2px solid #fff;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      background-color: #111;
      border-top: 2px solid #ff0000;
    }
  </style>
</head>
<body>
  <header>
    <h1>🎉 Noche Sobrenatural 🎉</h1>
    <p>Compra tu entrada y vive la experiencia más intensa</p>
  </header>

  <div class="container">
    <div class="tickets">
      <div class="ticket">
        <h2>Entrada General</h2>
        <div class="price">S/ 30</div>
        <div class="details">
          Pulsera Sobrenatural + Will o limón bokca gratis.
        </div>
        <canvas id="qr-general"></canvas>
        <p>Escanea con Yape</p>
      </div>

      <div class="ticket">
        <h2>Entrada Platino</h2>
        <div class="price">S/ 50</div>
        <div class="details">
          3 cócteles + pulsera Sobrenat
