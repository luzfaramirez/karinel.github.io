<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8"> <!-- Codificación de caracteres -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsivo para dispositivos móviles -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"> <!-- Enlace a Bootstrap CSS -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"> <!-- Enlace a fuente Roboto -->
    <link rel="stylesheet" href="./stylesheet/style.css">
    <link rel="stylesheet" href="./stylesheet/footer.css">
    <title>Menú Sobre Imagen</title> <!-- Título de la página -->
</head>
<body>
    <head>
        <style>
            .nav-link {
                color: #fff; /* Color por defecto del texto (blanco) */
            }
    
            .nav-link:hover,
            .nav-link:focus,
            .nav-link:active {
                color: #ff966d; /* Cambia este color al café que prefieras */
                text-decoration: none; /* Opcional: quita el subrayado */
            }
    
            .dropdown-item:hover {
                background-color: #6f4c3e; /* Cambia el fondo del ítem del menú desplegable al pasar el ratón */
                color: #fff; /* Cambia el color del texto en el ítem del menú desplegable */
            }
        </style>
    </head>
    
        <div class="position-relative">
            <img src="./images/foto 1 home.jpg" alt="Imagen de Fondo" class="bk-image"> <!-- Imagen de fondo -->
    
            <div class="overlay-title position-absolute bottom-0 start-0 mb-3 ms-3 text-white text-left">
                <h1>El crujido de mil hojas.</h1>
            </div>
    
            <nav class="menu container navbar navbar-expand-lg navbar-dark"> <!-- Barra de navegación -->
                <img src="./images/Logo KARINEL terciario 2.png" alt="Logo" class="logo"> <!-- Logo de la página -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"> <!-- Botón para menú hamburguesa -->
                    <span class="navbar-toggler-icon"></span> <!-- Icono del menú hamburguesa -->
                </button>
                <div class="collapse navbar-collapse" id="navbarNav"> <!-- Contenido colapsable del menú -->
                    <div class="d-flex flex-column flex-lg-row ms-auto"> <!-- Flexbox para alinear elementos -->
                        <a href="./index.html" class="nav-link me-4 home_menu">Home <img src="./images/Vector.png" alt="Home" style="width: 20px;"></a> <!-- Enlace Home -->
                        <div class="dropdown"> <!-- Menú desplegable -->
                            <a href="#" class="nav-link dropdown-toggle me-4 productos_menu" id="productosDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false"> <!-- Enlace Productos -->
                                Productos <img src="./images/pasteles.png" alt="Productos" style="width: 20px;">
                            </a>
                            <ul class="dropdown-menu" aria-labelledby="productosDropdown"> <!-- Contenido del menú desplegable -->
                                <li><a class="dropdown-item" href="./pasteles.html">Pasteles</a></li> <!-- Opción 1 -->
                                <li><a class="dropdown-item" href="./tortas.html">Tortas</a></li> <!-- Opción 2 -->
                                <li><a class="dropdown-item" href="./sandwiches.html">Sándwiches</a></li> <!-- Opción 3 -->
                                <li><a class="dropdown-item" href="./combos.html">Combos</a></li> <!-- Opción 4 -->
                                <li><a class="dropdown-item" href="./bebidas.html">Bebidas</a></li> <!-- Opción 5 -->
                            </ul>
                        </div>
                        <a href="./pedidos.html" class="nav-link me-4 pedidos_menu">Pedidos <img src="./images/pedidos.png" alt="Pedidos" style="width: 20px;"></a> <!-- Enlace Pedidos -->
                    </div>
                </div>
            </nav>
        </div>
    
    
    <!-- POSIBLES CARDS 3 -->
    
    <div class="container my-5">
        <!-- historia -->
        <h1 class="text-center titulo_hechoamano">HECHO A MANO DESDE 1998</h1>
        <h6 class="text-center historia_parrafo">El Salón de Té Karinel, ubicado en Sucre, Bolivia, es un emblemático establecimiento con una rica historia que data de varias décadas atrás. Fundado por una familia local, Karinel se ha convertido en un lugar de referencia para los residentes y visitantes de Sucre, ofreciendo una variedad de tés y pasteles tradicionales.</h6>
        
        <!-- temian la historia -->
        <!-- empiezan las cards -->
        <div class="row g-4">
            <div class="col-12 col-md-6 col-lg-4">
                <div class="card text-center shadow">
                    <img src="./images/BLANQUEADITAS.jpg" class="card-img-top" alt="Blanqueaditas">
                    <div class="card-body">
                        <!-- Cambiar tipografía del título de Blanqueaditas -->
                        <h5 class="card-title bl_title_blanqueaditas">Blanqueaditas</h5>
                        <!-- Cambiar tipografía del texto de Blanqueaditas -->
                        <p class="card-text bl_text_blanqueaditas">Bs. 3</p>
                        <!-- Cambiar estilo del botón de Blanqueaditas -->
                        <a href="./pedidos.html" class="btn btn-warning bl_btn_blanqueaditas">Pedir</a>
                    </div>
                </div>
            </div>
            
            <div class="col-12 col-md-6 col-lg-4">
                <div class="card text-center shadow">
                    <img src="./images/SANDWIXH.jpg" class="card-img-top" alt="Jamón y queso">
                    <div class="card-body">
                        <!-- Cambiar tipografía del título de Jamón y queso -->
                        <h5 class="card-title bl_title_jamon">Jamón y queso</h5>
                        <!-- Cambiar tipografía del texto de Jamón y queso -->
                        <p class="card-text bl_text_jamon">Bs. 8</p>
                        <!-- Cambiar estilo del botón de Jamón y queso -->
                        <a href="./pedidos.html" class="btn btn-warning bl_btn_jamon">Pedir</a>
                    </div>
                </div>
            </div>
            
            <div class="col-12 col-md-6 col-lg-4">
                <div class="card text-center shadow">
                    <img src="./images/COMBOS.jpg" class="card-img-top" alt="Pie de manzana">
                    <div class="card-body">
                        <!-- Cambiar tipografía del título de Pie de manzana -->
                        <h5 class="card-title bl_title_pie">Pie de manzana</h5>
                        <!-- Cambiar tipografía del texto de Pie de manzana -->
                        <p class="card-text bl_text_pie">Bs. 10</p>
                        <!-- Cambiar estilo del botón de Pie de manzana -->
                        <a href="./pedidos.html" class="btn btn-warning bl_btn_pie">Pedir</a>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="container my-5">
            <div class="row g-4">
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card text-center shadow">
                        <img src="./images/PIE.jpg" class="card-img-top" alt="Blanqueaditas">
                        <div class="card-body">
                            <!-- Cambiar tipografía del título de Blanqueaditas -->
                            <h5 class="card-title bl_title_blanqueaditas2">Blanqueaditas</h5>
                            <!-- Cambiar tipografía del texto de Blanqueaditas -->
                            <p class="card-text bl_text_blanqueaditas2">Bs. 3</p>
                            <!-- Cambiar estilo del botón de Blanqueaditas -->
                            <a href="./pedidos.html" class="btn btn-warning bl_btn_blanqueaditas2">Pedir</a>
                        </div>
                    </div>
                </div>
                
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card text-center shadow">
                        <img src="./images/PENKO.jpg" class="card-img-top" alt="Jamón y queso">
                        <div class="card-body">
                            <!-- Cambiar tipografía del título de Jamón y queso -->
                            <h5 class="card-title bl_title_jamon2">Jamón y queso</h5>
                            <!-- Cambiar tipografía del texto de Jamón y queso -->
                            <p class="card-text bl_text_jamon2">Bs. 8</p>
                            <!-- Cambiar estilo del botón de Jamón y queso -->
                            <a href="./pedidos.html" class="btn btn-warning bl_btn_jamon2">Pedir</a>
                        </div>
                    </div>
                </div>
                
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card text-center shadow">
                        <img src="./images/Fotografía (19 de 154).jpg" class="card-img-top" alt="Pie de manzana">
                        <div class="card-body">
                            <!-- Cambiar tipografía del título de Pie de manzana -->
                            <h5 class="card-title bl_title_pie2">Pie de manzana</h5>
                            <!-- Cambiar tipografía del texto de Pie de manzana -->
                            <p class="card-text bl_text_pie2">Bs. 10</p>
                            <!-- Cambiar estilo del botón de Pie de manzana -->
                            <a href="./pedidos.html" class="btn btn-warning bl_btn_pie2">Pedir</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- SLIDER NUEVO -->
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="./images/Fotografía (10 de 154).jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="./images/Fotografía (15 de 154).jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="./images/Fotografía (19 de 154).jpg" class="d-block w-100" alt="...">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>

    </body>
        <!-- SLIDER NUEVO -->

        <footer class="footer custom-footer py-4">
          <div class="container-fluid px-0"> <!-- Mantener container-fluid sin padding -->
              <div class="row text-center text-md-start">
                  <!-- Logo y nombre de la empresa -->
                  <div class="col-md-3 mb-4 mb-md-0">
                      <img src="./images/Logo KARINEL terciario 2.png" alt="Logo Karinel" class="img-fluid mb-2" style="max-width: 120px;">
                  </div>
      
                  <!-- Donde nos encontramos -->
                  <div class="col-md-3 mb-4 mb-md-0">
                      <h5 class="footer-heading">Donde nos encontramos</h5>
                      <ul class="list-unstyled">
                          <li>Calle J. J. Pérez #373</li>
                          <li>Sucre, Bolivia</li>
                      </ul>
                  </div>
      
                  <!-- Redes Sociales -->
                  <div class="col-md-3 mb-4 mb-md-0">
                      <h5 class="footer-heading">Social Media</h5>
                      <ul class="list-unstyled">
                          <li><a href="#" class="footer-link">Facebook</a></li>
                          <li><a href="#" class="footer-link">Instagram</a></li>
                      </ul>
                  </div>
      
                  <!-- Pedidos y Contactos -->
                  <div class="col-md-3 mb-4 mb-md-0">
                      <h5 class="footer-heading">Pedidos</h5>
                      <ul class="list-unstyled">
                          <li>Contactos</li>
                          <li>72866979</li>
                          <li>64-38672</li>
                      </ul>
                  </div>
              </div>
      
              <!-- Copyright -->
              <div class="row mt-4">
                  <div class="col text-center">
                      <p class="footer-text">&copy; Copyright 2024 - Karinel</p>
                  </div>
              </div>
          </div>
      </footer>



    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script> <!-- Popper.js para los dropdowns -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"></script> <!-- Bootstrap JS -->
</body>
</html>
