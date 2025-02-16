<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="AquaRide - El pont per a les millors botigues d'esports d'aigua online. Troba ofertes, taules, foils i més.">
  <meta name="keywords" content="esports aigua, surf, paddlesurf, wingfoil, kitesurf, foil, skatesurf, skate, equipament esports aigua">
  <title>AquaRide - Botigues d'Esports d'Aigua</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
</head>
<body>
  <!-- Barra de navegació -->
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a class="navbar-brand" href="#">AquaRide</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#botigues">Botigues</a></li>
          <li class="nav-item"><a class="nav-link" href="#ofertes">Ofertes</a></li>
          <li class="nav-item"><a class="nav-link" href="#categories">Categories</a></li>
          <li class="nav-item"><a class="nav-link" href="#contacte">Contacte</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Secció Hero -->
  <section class="hero-section">
    <div class="container text-center text-white">
      <h1>Benvingut a AquaRide</h1>
      <p>El pont per a les millors botigues d'esports d'aigua online</p>
      <form class="d-flex justify-content-center">
        <input id="search-input" class="form-control me-2" type="search" placeholder="Cerca productes...">
        <button class="btn btn-primary" type="submit">Cerca</button>
      </form>
    </div>
  </section>

  <!-- Secció de Botigues Associades -->
  <section id="botigues" class="container my-5">
    <h2>Botigues Associades</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="shop-card">
          <img src="https://images.pexels.com/photos/163210/moments-sport-leisure-surf-163210.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Botiga Surf">
          <h3>Botiga de SURF</h3>
          <p>Taules, vestits i accessoris per a surfistes.</p>
          <a href="#" class="btn btn-primary">Visita la botiga</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="shop-card">
          <img src="https://images.pexels.com/photos/847393/pexels-photo-847393.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Botiga PADDLESURF">
          <h3>Botiga de PADDLESURF</h3>
          <p>Pals i taules per a paddlesurf.</p>
          <a href="#" class="btn btn-primary">Visita la botiga</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="shop-card">
          <img src="https://images.pexels.com/photos/847393/pexels-photo-847393.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Botiga WingFoil">
          <h3>Botiga de WingFoil</h3>
          <p>Equipament complet per a WingFoil.</p>
          <a href="#" class="btn btn-primary">Visita la botiga</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Peu de pàgina -->
  <footer class="footer">
    <div class="container text-center">
      <p>&copy; 2023 AquaRide. Tots els drets reservats.</p>
      <div>
        <a href="#" class="text-light me-3"><i class="fab fa-facebook"></i></a>
        <a href="#" class="text-light me-3"><i class="fab fa-twitter"></i></a>
        <a href="#" class="text-light"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
