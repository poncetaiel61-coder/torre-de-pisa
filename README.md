<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Torre de Pisa - Bilingüe</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      margin: 0;
      padding: 0;
    }
    header {
      background: #c0392b;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      max-width: 900px;
      margin: auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    /* Pestañas */
    .tabs {
      display: flex;
      border-bottom: 2px solid #c0392b;
      margin-bottom: 20px;
      cursor: pointer;
      user-select: none;
    }
    .tab {
      flex: 1;
      padding: 15px;
      background: #eee;
      color: #333;
      text-align: center;
      font-weight: bold;
      border-top-left-radius: 8px;
      border-top-right-radius: 8px;
      transition: background 0.3s;
    }
    .tab.active {
      background: #c0392b;
      color: white;
    }
    /* Contenido pestañas */
    .tab-content {
      display: none;
    }
    .tab-content.active {
      display: block;
    }

    img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
      height: auto;
    }

    h2 {
      color: #c0392b;
      margin-top: 0;
    }
    ul {
      padding-left: 20px;
    }
    iframe {
      border: 0;
      border-radius: 8px;
      width: 100%;
      height: 300px;
    }
    footer {
      text-align: center;
      padding: 10px;
      background: #ddd;
      margin-top: 40px;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>

<header>
  <h1>Torre de Pisa - Bilingüe / Bilingual</h1>
</header>

<main>

  <div class="tabs">
    <div class="tab active" data-tab="es">🇪🇸 Español</div>
    <div class="tab" data-tab="en">🇬🇧 English</div>
  </div>

  <!-- Contenido Español -->
  <section id="es" class="tab-content active">
    <h2>La Torre de Pisa</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Leaning_Tower_of_Pisa_2013.jpg" alt="Torre de Pisa" />
    <p>La Torre de Pisa es un campanario famoso por su inclinación, ubicado en la ciudad de Pisa, Italia. Es parte de la Catedral de Pisa en la Piazza dei Miracoli.</p>
    <h3>Historia</h3>
    <p>La construcción comenzó en 1173 y debido a suelos inestables, la torre empezó a inclinarse desde el siglo XII. Fue estabilizada entre 1990 y 2001, logrando reducir su inclinación a aproximadamente 4 grados.</p>
    <h3>Datos Curiosos</h3>
    <ul>
      <li>Mide alrededor de 56 metros de altura.</li>
      <li>Inclina unos 4 grados tras los trabajos de estabilización.</li>
      <li>Es Patrimonio de la Humanidad desde 1987.</li>
    </ul>

    <h3>Hoteles cercanos</h3>
    <img src="https://cf.bstatic.com/xdata/images/hotel/max1024x768/279226009.jpg" alt="Hotel Pisa Tower" />
    <ul>
      <li><strong>Hotel Pisa Tower</strong> – Muy cerca de la torre, con terraza y jardín.</li>
    </ul>

    <img src="https://cdn.pixabay.com/photo/2017/01/12/19/55/terrace-1972721_1280.jpg" alt="Terraza Grand Hotel Duomo" />
    <ul>
      <li><strong>Grand Hotel Duomo</strong> – Hotel elegante con terraza panorámica y vistas a la torre.</li>
    </ul>

    <h3>Restaurantes</h3>
    <ul>
      <li><strong>Osteria dei Cavalieri</strong> – Restaurante toscano cerca de la torre.</li>
    </ul>

    <h3>Ubicación</h3>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2885.100032425755!2d10.395643515499168!3d43.723004879118504!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xf942521fa6a42f0!2sLeaning%20Tower%20of%20Pisa!5e0!3m2!1sen!2sit!4v1620225152296!5m2!1sen!2sit"
      allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <!-- Contenido Inglés -->
  <section id="en" class="tab-content">
    <h2>The Leaning Tower of Pisa</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Leaning_Tower_of_Pisa_2013.jpg" alt="Leaning Tower of Pisa" />
    <p>The Leaning Tower of Pisa is a famous bell tower known for its tilt, located in the city of Pisa, Italy. It is part of the Pisa Cathedral in the Piazza dei Miracoli.</p>
    <h3>History</h3>
    <p>Construction began in 1173 and due to unstable soil, the tower started leaning in the 12th century. It was stabilized between 1990 and 2001, reducing the tilt to approximately 4 degrees.</p>
    <h3>Interesting Facts</h3>
    <ul>
      <li>Measures about 56 meters tall.</li>
      <li>Leans about 4 degrees after stabilization work.</li>
      <li>UNESCO World Heritage Site since 1987.</li>
    </ul>

    <h3>Nearby Hotels</h3>
    <img src="https://cf.bstatic.com/xdata/images/hotel/max1024x768/279226009.jpg" alt="Hotel Pisa Tower" />
    <ul>
      <li><strong>Hotel Pisa Tower</strong> – Very close to the tower, with terrace and garden.</li>
    </ul>

    <img src="https://cdn.pixabay.com/photo/2017/01/12/19/55/terrace-1972721_1280.jpg" alt="Grand Hotel Duomo Terrace" />
    <ul>
      <li><strong>Grand Hotel Duomo</strong> – Elegant hotel with panoramic terrace and views of the tower.</li>
    </ul>

    <h3>Restaurants</h3>
    <ul>
      <li><strong>Osteria dei Cavalieri</strong> – Tuscan restaurant near the tower.</li>
    </ul>

    <h3>Location</h3>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2885.100032425755!2d10.395643515499168!3d43.723004879118504!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xf942521fa6a42f0!2sLeaning%20Tower%20of%20Pisa!5e0!3m2!1sen!2sit!4v1620225152296!5m2!1sen!2sit"
      allowfullscreen="" loading="lazy">
    </iframe>
  </section>

</main>

<footer>
  Página creada por Taiel Ponce / Page created by Taiel Ponce - © 2025
</footer>

<script>
  const tabs = document.querySelectorAll('.tab');
  const contents = document.querySelectorAll('.tab-content');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      // Quitar active de todas
      tabs.forEach(t => t.classList.remove('active'));
      contents.forEach(c => c.classList.remove('active'));

      // Activar la que se clickeó
      tab.classList.add('active');
      document.getElementById(tab.getAttribute('data-tab')).classList.add('active');
    });
  });
</script>

</body>
</html>

