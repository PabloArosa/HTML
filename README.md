# HTML
<!DOCTYPE html>
<html>

<head>
  <style>
    /* Estilos para el menú */
    .left-menu {
      float: left;
      width: 20%;
      height: 100%;
      background-color: #333;
      color: #fff;
    }

    .left-menu ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }

    .left-menu li a {
      display: block;
      padding: 15px;
      text-decoration: none;
      color: #fff;
    }

    .left-menu li a:hover {
      background-color: #555;
    }

    /* Estilos para el contenido */
    .main-content {
      float: left;
      width: 80%;
      padding: 20px;
    }
  </style>
</head>

<body>
  <div class="left-menu">
    <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Acerca de</a></li>
      <li><a href="#">Servicios</a></li>
      <li><a href="#">Contacto</a></li>
    </ul>
  </div>

  <div class="main-content">
    <h1>Bienvenido a mi sitio web</h1>
    <p>Este es el contenido principal de mi sitio web.</p>
  </div>
</body>

