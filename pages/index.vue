<template>
  <div class="body">
    <section id="title">
      <div class="container-fluid">
        <!-- Navbar -->
        <HomeCard />

        <div class="row header-style">
          <div class="col-lg-6">
            <h1>KetahUIparkir</h1>
            <p class="sub-header">
              Solusi permasalahan tempat parkir di Universitas Indonesia.
            </p>
            <button
              type="button"
              class="btn btn-lg redirect-button"
              onClick="document.getElementById('features').scrollIntoView();"
            >
              Keunggulan Fitur
            </button>
            <button
              type="button"
              class="btn btn-lg redirect-button"
              onClick="document.getElementById('design').scrollIntoView();"
            >
              Tentang Kami
            </button>
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
      <hr />
      <div class="row">
        <div class="feature-box col-lg-4 col-md-12 col-sm-12">
          <img src="../static/future_target.png" alt="target" />
          <h3>Tepat Sasaran</h3>
          <p>
            Memberikan rekomendasi tempat parkir berdasarkan tujuan kamu di UI,
            sehingga mencari parkir akan menjadi mudah, bahkan saat jam sibuk
            sekalipun.
          </p>
        </div>
        <div class="feature-box col-lg-4 col-md-12 col-sm-12">
          <img src="../static/mutakhir.png" alt="target" />
          <h3>Mutakhir</h3>
          <p>
            Data ketersediaan tempat parkir selalu diperbarui secara berkala,
            memastikan informasi yang aktual dan akurat.
          </p>
        </div>
        <div class="feature-box col-lg-4 col-md-12 col-sm-12">
          <img src="../static/user_friendly.png" alt="target" />
          <h3>User-friendly</h3>
          <p>
            Antarmuka aplikasi yang intuitif, anti-ribet, dan bertema
            Universitas Indonesia.
          </p>
        </div>
      </div>
    </section>

    <!-- Video -->
    <section id="video">
      <h2>Introduction Video</h2>
      <hr />
      <div class="video-player">
        <iframe
          class="responsive-iframe"
          src="https://youtube.com/embed/Y_srjElGIOg"
        ></iframe>
      </div>
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

    <!-- <section id="portfolio">
      <h2 class="portfolio-title">Screenshots</h2>
      <div>
        <b-carousel
          id="carousel-fade"
          style="text-shadow: 0px 0px 2px #000"
          fade
          indicators
          img-width="1024"
          img-height="480"
        >
          <b-carousel-slide
            caption="First slide"
            img-src="https://picsum.photos/1024/480/?image=10"
          ></b-carousel-slide>
          <b-carousel-slide
            caption="Second Slide"
            img-src="https://picsum.photos/1024/480/?image=12"
          ></b-carousel-slide>
          <b-carousel-slide
            caption="Third Slide"
            img-src="https://picsum.photos/1024/480/?image=22"
          ></b-carousel-slide>
        </b-carousel>
      </div>
    </section> -->
    
    <section class="design" id="design">
      <div class="container">
        <div class="row align-items-lg-center">
          <div class="col-12 col-md-6">
            <div class="section-heading mb-3">
              <h4>Ketahui</h4>
              <h1 class="display-4">Aplikasi Kami</h1>
            </div>
            <img
              class="img-fluid"
              src="https://assets.website-files.com/5e51c674258ffe10d286d30a/5e5363188becbffe8c57172c_peep-standing-24.svg"
              alt=""
            />
          </div>
          <div class="col-12 col-md-6">
            <div class="section-heading">
              <h1 class="display-6">Apa itu KetahUIparkir?</h1>
            </div>
            <img
              class="img-fluid mb-3"
              src="https://www.sevva.xyz/static/media/phone2.46e15ec8.png"
              alt=""
            />
            <p>
              KetahUIparkir merupakan aplikasi berbasis IOS dan Android yang
              dapat membantu penggunanya untuk mendapatkan parkir dengan
              cepat dan mudah di lingkup daerah Universitas Indonesia.
              KetahUIparkir memanfaatkan machine learning dan cloud
              computing untuk mendeteksi lokasi parkir yang paling baik
              untuk Anda. Sehingga, Anda tidak perlu lagi lama untuk mencari
              parkir di UI!
            </p>
          </div>
        </div>
      </div>
    </section>
      

    <section class="about" id="about">
      <div class="container">
        <div class="row align-items-lg-center">
          <div class="col-12 col-md-6">
            <div class="section-heading mb-3">
              <h4>Ketahui</h4>
              <h1 class="display-4">Cerita Kami</h1>
            </div>
            <p>
              Kami adalah mahasiswa-mahasiswi Teknik Komputer Universitas Indonesia 
              angkatan 2018 yang ingin membuat sebuah perubahan 
              pada lingkungan kami. 
            </p>
            <a class="btn mt-4 mb-5 mb-md-0 contact-button" href="/faq"
              >Find out more</a
            >
          </div>
          <div class="col-12 col-md-6">
            <img
              class="img-fluid"
              src="https://assets.website-files.com/5e51c674258ffe10d286d30a/5e535e9fc992502f35cd7902_peep-sitting-6.svg"
              alt="about"
            />
          </div>
        </div>
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
      <a href="/contact-us"
        ><button type="button" class="btn btn-dark btn-lg contact-button">
          Contact Us
        </button></a
      >
    </section>

    <!-- Footer -->
    <footer id="footer">
      <p>©Copyright {{ new Date().getFullYear() }} KetahUIparkir</p>
    </footer>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import HomeCard from "~/components/HomeCard.vue";

export default {
  components: {
    Logo,
    HomeCard,
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Arvo:ital,wght@0,400;0,700;1,400;1,700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500;1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700&display=swap");

.body {
  scroll-behavior: smooth;
}
#title {
  background: linear-gradient(rgba(16, 29, 44, 0.95), rgba(16, 29, 44, 0.95)),
    url("https://images.unsplash.com/photo-1506521781263-d8422e82f27a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1350&q=80");
  background-repeat: no-repeat;
  background-size: 100%;
  background-position-x: center;
  background-position-y: center;
  color: white;
}

#features {
  padding: 5% 15%;
  background-color: #ffff;
  text-align: center;
}

#about {
  padding: 60px 0;
}

#design {
  padding: 60px 0;
}

.feature-box {
  padding: 5%;
}

.feature-icon {
  margin-bottom: 1rem;
  color: #e08f62;
}

.feature-icon:hover {
  color: #cc7351;
}

.header-style h1 {
  font-family: "Playfair Display", serif;
  font-style: italic;
  font-weight: 700;
  font-size: 300%;
}

h1 {
  font-family: "Nunito";
  font-weight: 900;
  font-size: 3.5rem;
  line-height: 1.5;
}

h2 {
  font-family: "Nunito";
  font-size: 3rem;
  line-height: 1.5;
}

h3 {
  font-family: "Nunito";
  font-size: 1.5rem;
}

p {
  font-family: "Nunito";
  color: #696969;
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
  font-family: "Nunito";
  font-size: 2rem;
}

.nav-link {
  font-size: 1.25rem;
}

.navbar-align {
  margin-left: auto;
}

.nav-font {
  font-family: "Nunito";
}

.sub-header {
  font-size: 1.5em;
  font-family: "Nunito";
  color: #fff;
}

/* Redirect Buttons */

.redirect-button {
  margin: 5% 3% 5% 0;
  color: #ffff !important;
  transition: background-color 650ms;
  /* border-color: #203980; */
  font-family: "Nunito";
}

.redirect-button:hover {
  color: #fff !important;
  background-color: #203980;
}

/* Title Image */

.title-image {
  width: 100%;
}

/* Video Style */

#video {
  padding: 5% 15%;
  background-color: #eeec7665;
  text-align: center;
}

.video-player {
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%;
}

.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
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
  font-family: "Nunito";
}

#footer {
  text-align: center;
}

.section-heading h4 {
  text-transform: uppercase;
  line-height: 0;
  font-family: sans-serif;
  font-weight: 300;
  letter-spacing: 1px;
}

.section-heading h1 {
  font-family: cursive;
}

#about {
  background-color: #eeec7665;
}

.about .btn {
  width: 150px;
  color: #e08f62 !important;
  transition: background-color 650ms;
  border-color: #e08f62;
}

.about .btn:hover {
  color: #fff !important;
  background-color: #e08f62;
}

.test {
  display: flex;
}
</style>
