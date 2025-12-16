<html class="no-js" lang="">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title></title>
  <link rel="stylesheet" href="css/style.css">
  <meta name="description" content="">


  <link rel="manifest" href="site.webmanifest">
  <meta name="theme-color" content="#fafafa">

  <style>
    .my-button {
      padding: 15px 30px;       /* vertical and horizontal size */
      font-size: 18px;           /* text size */
      margin: 10px;              /* spacing between buttons */
      cursor: pointer;           /* pointer on hover */
      border-radius: 8px;        /* rounded corners */
      border: 1px solid #ffffff;    /* optional border */
      transition: transform 0.2s, background-color 0.2s; /* smooth hover effect */
    }

    /* Hover effect to scale buttons slightly */
    .my-button:hover {
      transform: scale(1.3);
      background-color: #4c4c4c; /* optional hover color */
    }

    h1 {text-align: center;}
    p {text-align: center;}

    body {

      background-image: url('Background.jpeg'); /* cesta k tvému JPEG */
      background-size: cover;   /* obrázek vyplní celé pozadí */
      background-repeat: no-repeat; /* obrázek se nebude opakovat */
      background-position: center 333px; /* horizontally center, 50px from the top */
    }

  </style>

</head>

<body>


<div style="text-align: center;">
  <h3>Projekt:</h3>
  <h1>Správa chodníku</h1>
  <h2>Kryštof J. Kovalský</h2>

  <button onclick="Kostky()" class="my-button">Kostky</button>
  <button onclick="Prostor()" class="my-button">Prostor</button>
  <button onclick="Cena()" class="my-button">Cena</button>
</div>
<img src="Dira2.jpeg" alt="My photo"
     style="position: absolute; top: 30px; left: 50px; width: 200px;">
<img src="Dira1.jpeg" alt="My photo"
     style="position: absolute; top: 30px; left: 1150px; width: 250px;">
<p id="output"></p> <!-- This is where the text will appear -->

<script>
  function Kostky() {
    let condition = true; // change this to whatever your condition is
    if (condition) {
      document.getElementById("output").innerText = "Kostky mají velikost přibližně 7² cm, neboli 343cm3.   " +
        "Kostek budeme pořrebovat přibližně 30.   " +
        "Naše kostky by měly co nejlépe zapadnout mezi ostatni, protože se nachazíme v památkářském areálu.   " +
        "Moc oceníme když přispějete na správu našeho chodníku" +
        "";
    } else {
    }
  }
  function Prostor() {
    let condition = true; // change this to whatever your condition is
    if (condition) {
      document.getElementById("output").innerText = "Prostory k zaplnění kostkami je 0,35 m².   " +
        "Prostory k zaplnění jsou celkem 2.   " +
        "Jeden prostor můžeme nalezézt poblíž pravých schodů (od budovy).   " +
        "Druhý prostor najdeme poblíž horního kaštanového stromu.   " +
        "Najdete je oba?   " +
        "Pokud naleznete další, prosím dejte nám vědět.   ";
    } else {
    }
  }
  function Cena() {
    let condition = true; // change this to whatever your condition is
    if (condition) {
      document.getElementById("output").innerText = "Cena jedné kostky je přibližně 7 CZK.   " + "Kostky se ale prodávají na váhu, proto je hodnota orientační.   " +
        "Pokud budeme potřebovat 35 kostek, cena bude přibližně 250 czk.   " +
        "250 korun je ale jen čistě materiál, stále musíme pokrýt doručení a umístění.   " +
        "V případě že by doručení a instalaci dělal někdo externí, částa by se mohla pohybovat ve větších jednotkách.   ";
    } else {
    }
  }
</script>



















  <script src="js/app.js"></script>

</body>
</html>
