<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ristorante - Benvenuti</Kebhub>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
      color: #333;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
      position: relative;
    }
    header img {
      width: 150px;
    }
    header a {
      position: absolute;
      right: 20px;
      top: 50%;
      transform: translateY(-50%);
      padding: 10px 20px;
      background-color: #FFA500;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }
    .section {
      padding: 50px;
      text-align: center;
    }
    .map-container {
      width: 100%;
      height: 400px;
      margin: 20px 0;
    }
    .gallery {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .gallery img {
      width: 200px;
      margin: 10px;
      border-radius: 10px;
    }
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <img src="tuo_logo.png" alt="Logo Ristorante">
  <a href="#menu">Vedi il menu</a>
</header>

<section class="section">
  <h1>Benvenuti al [Nome del Ristorante]</h1>
  <p>Scopri la nostra cucina e vieni a trovarci per un'esperienza culinaria unica!</p>
</section>

<section class="section">
  <h2>Dove siamo</h2>
  <p>Indirizzo: Via Esempio 123, Città</p>
  <div class="map-container">
    <!-- Qui puoi incorporare Google Maps -->
    <iframe src="https://www.google.com/maps/embed?pb=!1m18..."></iframe>
  </div>
  <a href="https://maps.google.com" target="_blank">Ottieni indicazioni</a>
</section>

<section class="section">
  <h2>I nostri piatti</h2>
  <div class="gallery">
    <img src="piatto1.jpg" alt="Piatto 1">
    <img src="piatto2.jpg" alt="Piatto 2">
    <img src="piatto3.jpg" alt="Piatto 3">
    <!-- Aggiungi altre immagini -->
  </div>
</section>

<section class="section">
  <h2>Contattaci</h2>
  <p>Email: info@ristorante.com</p>
  <p>Telefono: 123-456-7890</p>
</section>

<footer>
  <p>&copy; 2024 [Nome del Ristorante]. Tutti i diritti riservati.</p>
</footer>

</body>
</html>
