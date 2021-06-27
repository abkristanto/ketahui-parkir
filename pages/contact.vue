<template>
  <div class="body">
    <section id="title">
      <div class="container-fluid">
          <!-- Navbar -->
          <nav class="navbar navbar-expand-lg navbar-dark">
              <a class="navbar-brand" href="index.html">photatoes</a>
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01"
                  aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
                  <ul class="navbar-nav ml-auto">
                      <li class="nav-item">
                          <a class="nav-link" href="contact.html">Contact</a>
                      </li>  
                      <li class="nav-item">
                          <a class="nav-link" href="">About Us</a>
                      </li>
                  </ul>
              </div>
          </nav>
          <!-- Navbar -->
          <div class="row">
              <div class="col-lg-6">
                  <h1>Contact Information</h1>
                  <a href="https://www.instagram.com/photato.e/"><button type="button"
                          class="btn btn-dark btn-lg download-button"><i class="fab fa-instagram"></i>
                          Instagram</button></a>
                  <a href="index.html"><button type="button" class="btn btn-outline-light btn-lg download-button"
                          onClick="document.getElementById('portfolio').scrollIntoView();">Photo Gallery</button></a>
                  <h3>This is our contact information for now. Coming soon.</h3>
              </div>
              <div class="col-lg-6">
                  <img class="title-image" src="images/photatoes.jpg" alt="camera-photo">
              </div>
          </div>
      </div>
  </section>
  <section id="features">
      <div class="row">
          <div class="feature-box col-lg-4 col-md-12 col-sm-12">
              <i class="fab fa-instagram fa-5x feature-icon"></i>
              <h3>Abraham's Instagram</h3>
              <p>@abkristanto</p>
          </div>
          <div class="feature-box col-lg-4 col-md-12 col-sm-12">
              <i class="fab fa-instagram fa-5x feature-icon"></i>
              <h3>Ketahui Parkir's Instagram</h3>
              <p>@ketahuiparkirui</p>
          </div>
          <div class="feature-box col-lg-4 col-md-12 col-sm-12">
              <i class="fab fa-instagram fa-5x feature-icon"></i>
              <h3>Main Instagram</h3>
              <p>@photato.e</p>
          </div>
      </div>
    </section>
  </div>
</template>


<style>
.body {
  scroll-behavior: smooth;
}
#title {
    background-color: #cc7351;
    color: white;
}

#features {
    padding: 5% 15%;
}

.feature-box {
    text-align: center;
    padding: 5%;
}

.feature-icon {
    margin-bottom: 1rem;
    color:#e08f62;
}

.feature-icon:hover {
    color: #cc7351;
}

h1 {
    font-family: "Montserrat", sans-serif;
    font-weight: 900;
    font-size: 3.5rem;
    line-height: 1.5;
}

h2 {
    font-family: "Montserrat", sans-serif;
    font-size: 3rem;
    line-height: 1.5;
}

h3 {
    font-family: "Montserrat", sans-serif;
    font-size: 1.5rem;
}

p {
    color: #8f8f8f;
}

.container-fluid {
    padding: 3% 15%;
}

/* Navigation Bar */

.navbar {
    padding: 0 0 3.5rem;
}

.navbar-brand {
    font-family: "Ubuntu";
    font-size: 2rem;
}

.nav-link {
    font-size:1.25rem;
}

/* Download Buttons */

.download-button {
    margin: 5% 3% 5% 0;
}

/* Title Image */

.title-image {
    width: 100%;
}

#testimonials {
    padding: 5% 15%;
    text-align: center;
    background-color: #9dab86;
    color: #fff;
}

.testimonial-image {
    width: 15%;
    border-radius: 100%;
    margin: 20px;
}

#portfolio {
    padding: 5% 15%;
}

.portfolio-title {
    text-align: center;
}

#pricing {
    padding: 5% 15%;
    text-align: center;
    background-color: #9dab86;
    color: #fff;
}

.pricing-plan {
    padding-top: 5%;
}

.price-description {
    color: #fff;
}

.pricing-button {
    margin: 0 0 5% 0;
}

#cta {
    padding: 5% 15%;
    text-align: center;
}

.contact-button {
    margin-top: 30px;
}

#footer {
    text-align: center;
}
</style>