<template>
  <div class="body">
    <section id="title">
      <div class="container-fluid">
        <!-- Navbar -->
        <HomeCard />
        
        <div class="row">
          <div class="col-lg-6">
            <h1>KetahUIparkir</h1>
            <p class="sub-header">Solusi permasalahan tempat parkir di Universitas Indonesia.</p>
            <button type="button" class="btn btn-dark btn-lg download-button" onClick="document.getElementById('features').scrollIntoView();">Overview</button>
            <button type="button" class="btn btn-outline-light btn-lg download-button" onClick="document.getElementById('portfolio').scrollIntoView();">Screenshots</button>
          </div>
          <!--<div class="col-lg-6">
            <img class="title-image" src="images/camera.jpg" alt="camera-photo">
          </div> -->
        </div>
      </div>
    </section>

    <!-- Features -->

    <section id="features">
      <h2>Keunggulan Kami</h2>
      <hr>
      <div class="row">
        <div class="feature-box col-lg-4 col-md-12 col-sm-12">
          <i class="fas fa-stopwatch fa-5x feature-icon"></i>
          <h3>Flexible workflow</h3>
          <p>Capture every special moment with the best clarity.</p>
        </div>
        <div class="feature-box col-lg-4 col-md-12 col-sm-12">
          <i class="fas fa-camera-retro fa-5x feature-icon"></i>
          <h3>Elite Photography Skills</h3>
          <p>Creative perspective with award-winning photographers.</p>
        </div>
        <div class="feature-box col-lg-4 col-md-12 col-sm-12">
          <i class="far fa-check-circle fa-5x feature-icon"></i>
          <h3>Guaranteed results</h3>
          <p>Prints, edited and unedited files are all included in the bundle.</p>
        </div>
      </div>
    </section>

    <!-- Video -->
    <section id="video">
      <h2>Introduction Video</h2>
      <hr>
      <iframe src="https://youtube.com/embed/Y_srjElGIOg" width="854" height="480"></iframe>
    </section>

    <!-- Testimonials -->
    <!--
    <section id="testimonials">
      <h2>I no longer need to worry about missing out on unforgettable moments. I now know who to call when I know I want
        amazing photos. Definitely a must!</h2>
      <img class="testimonial-image" src="images/woman.jpg" alt="bali-scenery" width="100%" height="auto">
      <em>Natasha, Long Island</em>
    </section>
    -->

    <!-- Portfolio -->

    <section id="portfolio">
      <h2 class="portfolio-title">Screenshots</h2>
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../static/KetahUIparkir Location choose.png" class="d-block w-100 img-screenshot" alt="Dashboard">
          </div>
          <div class="carousel-item">
            <img src="../static/KetahUIparkir Location choose.png" class="d-block w-100 img-screenshot" alt="Location choose">
          </div>
          <div class="carousel-item">
            <img src="../static/KetahUIparkir Recommendation.png" class="d-block w-100 img-screenshot" alt="Recommendation">
          </div>
          <div class="carousel-item">
            <img src="../static/KetahUIparkir Account History.png" class="d-block w-100 img-screenshot" alt="Account History">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon back-black" aria-hidden="true"></span>
          <span class="sr-only text-black">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon next-black" aria-hidden="true"></span>
          <span class="sr-only text-black">Next</span>
        </a>
      </div>
    </section>

    <!-- Pricing -->
    <!--
    <section id="pricing">
      <h1>A plan for every moment</h1>
      <p class="price-description">Simple and affordable pricing bundles for you and your needs.</p>
      <div class="row pricing-plan">
        <div class="col-lg-4 col-md-12 col-sm-12">
          <h3>Trial</h3>
          <h2>Free</h2>
          <p class="price-description">5 photos, maximum 20 minute photoshoot</p>
          <p class="price-description">Free edited Prints</p>
          <button type="button" class="btn btn-outline-light btn-lg pricing-button">Sign up</button>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
          <h3>Full day</h3>
          <h2>Rp1.000.000,00</h2>
          <p class="price-description">Unlimited amount of photos</p>
          <p class="price-description">Full supply of prints in curated color palette, full access to digital files, RAW and JPEG.</p>
          <button type="button" class="btn btn-outline-light btn-lg pricing-button">Sign up</button>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
          <h3>Per hour</h3>
          <h2>Rp200.000,00</h2>
          <p class="price-description">Maximum 50 pictures per hour</p>
          <p class="price-description">Full supply of prints in curated color paltette. full access to digital files.</p>
          <button type="button" class="btn btn-outline-light btn-lg pricing-button">Sign up</button>
        </div>
      </div>

    </section>
    -->

    <section id="cta">
      <h3>Masih ragu? Langsung kontak kami saja!</h3>
      <a href="/contact-us"><button type="button" class="btn btn-dark btn-lg contact-button">Contact Us</button></a>
    </section>

    <!-- Footer -->
    <footer id="footer">
      <p>©Copyright {{new Date().getFullYear()}} KetahUIparkir</p>
    </footer>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import HomeCard from '~/components/HomeCard.vue'

export default {
  components: {
    Logo,
    HomeCard,
  }
}

</script>

<style>
.body {
  scroll-behavior: smooth;
}
#title {
    background-image: url("\static\Parking camera.jpg");
    background-repeat: no-repeat;
    background-size: 100%;
    color: white;
}

#features {
    padding: 5% 15%;
    background-color: #FFEE0A;
    text-align: center;
}

.feature-box {
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

.text-black {
    color: #000;
}

.back-black {
    background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23000'%3e%3cpath d='M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z'/%3e%3c/svg%3e");
}

.next-black {
    background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23000'%3e%3cpath d='M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");
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

.sub-header {
    font-size: 1.5em;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    color:#fff;
}

/* Download Buttons */

.download-button {
    margin: 5% 3% 5% 0;
}

/* Title Image */

.title-image {
    width: 100%;
}

/* Video Style */

#video {
    padding: 5% 15%;
    background-color: #C4C4C4;
    text-align: center;
}

/* Screenshot Style*/

.img-screenshot {
    width: auto;
    max-width: 30%;
    margin: 0 auto;
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
