<template>
  <!--Header-->
  <header id="Home" class="navbar navbar-expand-lg">
    <div class="container">
        <a class="navbar-brand" href="#Home">
            <img src="../assets/logo2.png" alt="Logo" class="logo">
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <i class="fa-solid fa-bars" style="color: #ffffff;"></i>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#Home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#About">About</a></li>
                <li class="nav-item"><a class="nav-link" href="#Gallery">Gallery</a></li>
                <li class="nav-item"><a class="nav-link" href="#Contact">Contact</a></li>
            </ul>
        </div>
    </div>
  </header>
  
  <br><br>

  <!-- Sección de about -->
  <div class="about-container">
    <div class="about">
  
      <div class="left-section">
        <img src="../assets/perfil.jpeg" alt="Foto de perfil">
      </div>
      
     
      <div class="right-section">
        
        <h1 id="About">Bienvenido a mi Portafolio</h1>
        <h3>Estudiante de la carrera de Entornos Virtuales y Negocios Digitales</h3>
        <br>
        <br>
        <h2>Sobre mí</h2>
        <p>¡Hola! Soy Ana Espinoza, una joven curiosa y apasionada por la tecnología y los negocios digitales. Estudio en la Universidad Tecnológica de la Riviera Maya, y disfruto explorar todo lo relacionado con la programación, la innovación y las nuevas herramientas digitales. Me encanta estar al tanto de las últimas tendencias y siempre busco formas de seguir aprendiendo y mejorando mis habilidades.</p>
      </div>
    </div>
  </div>



  <!-- Sección Galería -->
  <section class="my-gallery">
    <h1 id="Gallery" class="gallery-title">Galería de Proyectos</h1>

    <div class="row">
        <!-- Contenedor 1 -->
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="custom-gallery-item shadow">
                <img src="../assets/gallery3.jpeg" class="custom-img-fluid" alt="Imagen 1">
                <h5 class="custom-subtitle">1</h5>
                <p class="custom-description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus nesciunt, dolore suscipit voluptatem facere fuga incidunt, corrupti expedita exercitationem vero molestiae. Maxime pariatur animi distinctio expedita est officia velit doloremque!</p>
            </div>
        </div>

        <!-- Contenedor 2 -->
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="custom-gallery-item shadow">
                <img src="../assets/gallery3.jpeg" class="custom-img-fluid" alt="Imagen 1">
                <h5 class="custom-subtitle">2</h5>
                <p class="custom-description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus nesciunt, dolore suscipit voluptatem facere fuga incidunt, corrupti expedita exercitationem vero molestiae. Maxime pariatur animi distinctio expedita est officia velit doloremque!</p>
            </div>
        </div>

        <!-- Contenedor 3 -->
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="custom-gallery-item shadow">
                <img src="../assets/gallery3.jpeg" class="custom-img-fluid" alt="Imagen 1">
                <h5 class="custom-subtitle">3</h5>
                <p class="custom-description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus nesciunt, dolore suscipit voluptatem facere fuga incidunt, corrupti expedita exercitationem vero molestiae. Maxime pariatur animi distinctio expedita est officia velit doloremque!</p>
            </div>
        </div>
    </div>
  </section>

  <section class="my-gallery">
    <div class="row">
        <!-- Contenedor 4 -->
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="custom-gallery-item shadow">
                <img src="../assets/gallery3.jpeg" class="custom-img-fluid" alt="Imagen 1">
                <h5 class="custom-subtitle">4</h5>
                <p class="custom-description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus nesciunt, dolore suscipit voluptatem facere fuga incidunt, corrupti expedita exercitationem vero molestiae. Maxime pariatur animi distinctio expedita est officia velit doloremque!</p>
            </div>
        </div>

        <!-- Contenedor 5 -->
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="custom-gallery-item shadow">
                <img src="../assets/gallery3.jpeg" class="custom-img-fluid" alt="Imagen 1">
                <h5 class="custom-subtitle">5</h5>
                <p class="custom-description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus nesciunt, dolore suscipit voluptatem facere fuga incidunt, corrupti expedita exercitationem vero molestiae. Maxime pariatur animi distinctio expedita est officia velit doloremque!</p>
            </div>
        </div>

        <!-- Contenedor 6 -->
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="custom-gallery-item shadow">
                <img src="../assets/gallery3.jpeg" class="custom-img-fluid" alt="Imagen 1">
                <h5 class="custom-subtitle">6</h5>
                <p class="custom-description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus nesciunt, dolore suscipit voluptatem facere fuga incidunt, corrupti expedita exercitationem vero molestiae. Maxime pariatur animi distinctio expedita est officia velit doloremque!</p>
            </div>
        </div>
    </div>
  </section>


  
  <div class="d-flex justify-content-center align-items-center min-vh-100">
    <!-- Sección de contacto -->
    <section class="contact-form-section py-5">
      <div class="container">
        <h1 id="Contact" class="contact-form-title text-center mb-4">Formulario de Contacto</h1>

        <form action="#" method="POST" class="contact-form">
          <!-- Nombre -->
          <div class="mb-3">
            <label for="contact-name" class="form-label">Nombre</label>
            <input type="text" class="form-control shadow-sm" id="contact-name" placeholder="Tu nombre" required>
          </div>

          <!-- Correo -->
          <div class="mb-3">
            <label for="contact-email" class="form-label">Correo electrónico</label>
            <input type="email" class="form-control shadow-sm" id="contact-email" placeholder="Tu correo electrónico" required>
          </div>

          <!-- Mensaje -->
          <div class="mb-3">
            <label for="contact-message" class="form-label">Mensaje</label>
            <textarea class="form-control shadow-sm" id="contact-message" rows="5" placeholder="Escribe tu mensaje" required></textarea>
          </div>

          <!-- Botón de envío -->
          <button type="submit" class="btn btn-primary btn-lg w-100 shadow-sm">Enviar mensaje</button>
        </form>
      </div>
    </section>
  </div>





  <!-- Footer -->
  <footer class="footer-section bg-dark text-white pt-5 pb-4">
    <div class="container-fluid">
        <div class="row justify-content-center text-center">
            <!-- About Us Section -->
            <div class="col-md-4 col-sm-12 mb-4">
                <h5>About Us</h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam non urna nec nisi tincidunt volutpat.</p>
            </div>

            <!-- Quick Links Section -->
            <div class="col-md-4 col-sm-12 mb-4">
                <h5>Quick Links</h5>
                <ul class="list-unstyled">
                    <li><a href="#Home" class="quick-link">Home</a></li>
                    <li><a href="#About" class="quick-link">About</a></li>
                    <li><a href="#Gallery" class="quick-link">Gallery</a></li>
                    <li><a href="#Contact" class="quick-link">Contact</a></li>
                </ul>
            </div>

            <!-- Contact Section -->
            <div class="col-md-4 col-sm-12 mb-4">
                <h5>Contact</h5>
                <p>Email: 2314041@utrivieramaya.edu.mx</p>
                <p>Phone: +52 9841427515</p>
            </div>
        </div>

        <!-- Derechos reservados -->
        <div class="mt-3 text-center">
            <p class="mb-0">&copy; 2025. By Ana Espinoza. All rights reserved.</p>
        </div>

        <!-- Botón de subir -->
        <div class="text-center mt-3">
            <a href="#top" class="text-light">
                <i class='bx bxs-chevron-up' style='color:rgb(255, 1, 73); font-size: 24px;'></i>
            </a>
        </div>
    </div>
</footer>

</template>

<script>
export default {
  name: 'MyPortafolioAna',
  props: {
    msg: String
  }
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  line-height: 1.6;
  background-color: white !important;
  color: black;
  padding: 20px;
  margin: 0;
}

header {
  background-color: rgb(110, 17, 160);
  padding: 10px 0;
  margin-bottom: -20px;
}

.logo {
  height: 50px;
  margin-left: 200px;
}

.navbar-nav .nav-link {
  font-weight: 700;
  color: white;
  padding: 10px 15px;
  transition: 0.3s;
}

.navbar-nav .nav-link:hover {
  color: #F05966;
}

.navbar-toggler {
  border: none;
  background: transparent;
  margin-right: 30px;
  padding: 0;
  outline: none;
  box-shadow: none;
}

.navbar-toggler-icon {
  filter: invert(1);
}

@media (max-width: 991px) {
  .navbar-nav {
    text-align: right;
  }

  .navbar-nav .nav-item {
    margin-bottom: 1px;
  }

  .logo {
    height: 50px;
    margin-left: 50px;
  }
}

.about-container {
  margin-top: 0px;
}

.about {
  background-color: white !important;
  padding: 40px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.about .left-section {
  flex: 1;
  padding-right: 30px;
  text-align: center;
}

.about img {
  width: 220px;
  height: 220px;
  object-fit: cover;
  border-radius: 10%;
  border: 5px solid black;
  box-shadow: 0 0 30px rgb(110, 17, 160);
  transition: all 0.3s ease;
}

.about img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 30px #F05966;
}

.about .right-section {
  flex: 2;
  text-align: left;
}

.about h1 {
  font-size: 3.5em;
  color: black;
  font-weight: 700;
  margin-bottom: 20px;
  animation: fadeIn 1s ease-out;
}

.about h3 {
  font-size: 1.4em;
  color: gray;
  margin-bottom: 20px;
  animation: fadeIn 1s ease-out;
}

.about h2 {
  font-size: 2.5em;
  color: black;
  font-weight: 500;
  margin-bottom: 20px;
  animation: fadeIn 1s ease-out;
}

.about p {
  font-size: 1.1em;
  color: #666;
  line-height: 1.8;
  font-weight: 400;
  animation: fadeIn 1s ease-out;
  text-align: justify;
}

@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

@media (max-width: 768px) {
  .about {
    flex-direction: column;
    text-align: center;
    padding: 30px;
  }

  .about .left-section {
    padding-right: 0;
  }

  .about h1 {
    font-size: 2.8em;
  }

  .about h3 {
    font-size: 1.3em;
  }

  .about h2 {
    font-size: 2.2em;
  }
}

@media (max-width: 480px) {
  .about h1 {
    font-size: 2.3em;
  }

  .about h3 {
    font-size: 1.2em;
  }

  .about h2 {
    font-size: 1.8em;
  }

  .about img {
    width: 180px;
    height: 180px;
    margin-bottom: 40px;
  }
}

.my-gallery {
  margin-top: 50px;
  text-align: center;
}

.gallery-title {
  font-size: 30px;
  font-weight: 700;
  color: black;
  margin-bottom: 30px;
}

.custom-gallery-item {
  background-color: white;
  border-radius: 10px;
  padding: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  margin: 5px;
}

.custom-gallery-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.custom-img-fluid {
  border-radius: 10px;
  max-width: 100%;
  height: auto;
}

.custom-subtitle {
  font-size: 1.25rem;
  font-weight: bold;
  color: #d620e0;
  margin-top: 15px;
}

.custom-description {
  font-size: 0.9rem;
  color: #6c757d;
  margin-top: 10px;
}

@media (max-width: 768px) {
  .custom-gallery-item {
    padding: 15px;
  }

  .custom-subtitle {
    font-size: 1.1rem;
  }

  .custom-description {
    font-size: 0.85rem;
  }

  .gallery-title {
    font-size: 2.5em;
  }
}

@media (max-width: 480px) {
  .gallery-title {
    font-size: 2em;
  }

  .custom-subtitle {
    font-size: 1rem;
  }

  .custom-description {
    font-size: 0.8rem;
  }
}

.contact-form-section {
  background-color: white;
  padding: 30px;
}

.contact-form-title {
  font-size: 30px;
  font-weight: 700;
  color: black;
  margin-bottom: 30px;
}

.contact-form {
  max-width: 600px;
  margin: 0 auto;
}

.form-control:focus {
  box-shadow: 0 0 5px rgba(255, 0, 234, 0.5);
}

.btn button:hover {
  background-color: #d620e0 !important;
}
.btn {
  background-color: #F05966;
}

.d-flex {
  display: flex;
}

.justify-content-center {
  justify-content: center;
}

.align-items-center {
  align-items: center;
}

.min-vh-100 {
  min-height: 100vh;
}

@media (max-width: 768px) {
  .contact-form-section {
    padding: 20px;
  }

  .contact-form-title {
    font-size: 2em;
  }

  .contact-form {
    max-width: 90%;
  }

  .form-control {
    font-size: 1rem;
  }

  .btn button {
    font-size: 1.1rem;
    padding: 12px;
  }
}

@media (max-width: 576px) {
  .contact-form-title {
    font-size: 1.8em;
  }

  .form-control {
    font-size: 0.9rem;
  }

  .btn button {
    font-size: 1rem;
    padding: 10px;
  }
}

.footer-section {
  background-color:rgb(77, 14, 110) !important;
  color: white;
  padding-top: 50px;
  padding-bottom: 30px;
  
}

.footer-section a {
  text-decoration: none;
  color: white;
  transition: color 0.3s ease;
}

.footer-section a:hover {
  color: #F05966;
}

.footer-section .row {
  display: flex;
  justify-content: space-between;
  gap: 30px;
}

.footer-section .col-md-4, .footer-section .col-sm-12 {
  flex: 1 1 30%;
  padding: 0 15px;
}

.footer-section ul {
  padding-left: 0;
}

.footer-section .quick-link {
  display: block;
  padding: 5px 0;
}

@media (max-width: 767px) {
  .footer-section .row {
    display: block;
  }

  .footer-section .col-md-4 {
    width: 100%;
    margin-bottom: 20px;
  }

  .footer-section h5 {
    font-size: 1.2rem;
  }

  .footer-section p,
  .footer-section ul {
    font-size: 0.9rem;
  }
}

@media (min-width: 768px) {
  .footer-section .row {
    display: flex;
  }

  .footer-section .col-md-4 {
    width: 33.33%;
  }
}





</style>
