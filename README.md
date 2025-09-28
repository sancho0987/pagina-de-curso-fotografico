<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Curso Online de Fotografía</title>
  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Estilos -->
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    header {
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
      color: white;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      animation: fadeIn 2s ease-in-out;
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    .card img:hover {
      transform: scale(1.05);
      transition: 0.3s;
    }
    footer {
      background: #222;
      color: #ddd;
      padding: 20px 0;
    }
    footer a {
      color: #ddd;
      margin: 0 10px;
      text-decoration: none;
    }
    footer a:hover {
      color: white;
    }
  </style>
</head>
<body>


  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">FotoCurso</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
          <li class="nav-item"><a class="nav-link" href="#galeria">Galería</a></li>
          <li class="nav-item"><a class="nav-link" href="#precios">Precios</a></li>
          <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>


  <header>
    <div>
      <h1>Aprende Fotografía Digital</h1>
      <p class="lead">Curso online desde cero, domina la cámara y crea arte visual</p>
      <a href="#contacto" class="btn btn-primary btn-lg">Inscríbete Ahora</a>
    </div>
  </header>


  <section id="servicios" class="py-5 container">
    <h2 class="text-center mb-4">¿Qué aprenderás?</h2>
    <div class="row text-center">
      <div class="col-md-4">
        <div class="card shadow">
          <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Cámara">
          <div class="card-body">
            <h5 class="card-title">Manejo de Cámara</h5>
            <p class="card-text">Aprende a usar tu cámara en modo manual y controla la luz.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow">
          <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Edición">
          <div class="card-body">
            <h5 class="card-title">Edición Profesional</h5>
            <p class="card-text">Domina Lightroom y Photoshop para mejorar tus fotos.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow">
          <img src="img/mohsin-nisar-w5q7Jgc4KCQ-unsplash.jpg" class="card-img-top" alt="Composición">
          <div class="card-body">
            <h5 class="card-title">Composición</h5>
            <p class="card-text">Aprende reglas de composición para lograr fotos impactantes.</p>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section id="galeria" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">Galería de Estudiantes</h2>
      <div class="row g-3">
        <div class="col-md-4"><img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=600&q=80" class="img-fluid rounded shadow" alt="Foto 1"></div>
        <div class="col-md-4"><img src="https://images.unsplash.com/photo-1469474968028-56623f02e42e?auto=format&fit=crop&w=600&q=80" class="img-fluid rounded shadow" alt="Foto 2"></div>
        <div class="col-md-4"><img src="https://images.unsplash.com/photo-1495567720989-cebdbdd97913?auto=format&fit=crop&w=600&q=80" 
class="img-fluid rounded shadow" alt="Foto 3">></div>
      </div>
    </div>
  </section>

  <!-- TABLA -->
  <section id="precios" class="py-5 container">
    <h2 class="text-center mb-4">Planes y Precios</h2>
    <table class="table table-bordered text-center">
      <thead class="table-dark">
        <tr>
          <th>Plan</th>
          <th>Contenido</th>
          <th>Precio</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Básico</td>
          <td>
            <ul>
              <li>10 clases grabadas</li>
              <li>Acceso 1 mes</li>
            </ul>
          </td>
          <td>$50</td>
        </tr>
        <tr>
          <td>Intermedio</td>
          <td>
            <ul>
              <li>20 clases grabadas</li>
              <li>Acceso 3 meses</li>
              <li>Sesiones en vivo</li>
            </ul>
          </td>
          <td>$120</td>
        </tr>
        <tr>
          <td>Premium</td>
          <td>
            <ul>
              <li>40 clases grabadas</li>
              <li>Acceso 1 año</li>
              <li>Mentoría personalizada</li>
            </ul>
          </td>
          <td>$250</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- CONTACTO -->
  <section id="contacto" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">Contáctanos</h2>
      <form class="row g-3">
        <div class="col-md-6">
          <input type="text" class="form-control" placeholder="Tu Nombre" required>
        </div>
        <div class="col-md-6">
          <input type="email" class="form-control" placeholder="Tu Correo" required>
        </div>
        <div class="col-12">
          <textarea class="form-control" rows="4" placeholder="Escribe tu mensaje" required></textarea>
        </div>
        <div class="col-12 text-center">
          <button class="btn btn-dark btn-lg">Enviar</button>
        </div>
      </form>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="text-center">
    <p>© 2025 FotoCurso - Todos los derechos reservados</p>
    <p>
      <a href="#">Facebook</a> | 
      <a href="#">Instagram</a> | 
      <a href="#">Twitter</a>
    </p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
