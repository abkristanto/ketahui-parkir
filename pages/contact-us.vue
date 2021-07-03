<template>
  <div class="body">
    <section id="title">
      <div class="container-fluid">
          <!-- Navbar -->
          <HomeCard />
          <!-- Navbar -->
          <div class="row">
              <div class="col-lg-9">
                  <h1>Contact Us</h1>
                  <h3>Perlu bantuan atau ada masukan? Di sinilah tempat kamu bisa mengutarakannya!</h3>
              </div>
          </div>
      </div>
    </section>
    <section id="team">
        <h2 class="text-center">Meet Our Team</h2>
        <div class="row">
            <div class="feature-box col-lg-4 col-md-12 col-sm-12">
                <img class="portrait mb-3" src="../static/nadhifa_round.png">
                <h3>Nadhifa Khalisha Anandra</h3>
                <i class="text-threefourth">1806148800 / DPTK 1-01</i>
                <p></p>
                <a href="https://instagram.com/nadklisha"><img src="../static/Instagram icon.png" width="30" height="30"></a>
            </div>
            <div class="feature-box col-lg-4 col-md-12 col-sm-12">
                <img class="portrait mb-3" src="../static/dimas_round.png">
                <h3>Dimas Wira Nugraha</h3>
                <i class="text-threefourth">1806200021 / DPTK 1-01</i>
                <p></p>
            </div>
            <div class="feature-box col-lg-4 col-md-12 col-sm-12">
                <img class="portrait mb-3" src="../static/natalia_round.png">
                <h3>Natalia Kristian</h3>
                <i class="text-threefourth">1806200103 / DPTK 1-01</i>
                <p></p>
                <a href="https://instagram.com/natalia_k014"><img src="../static/Instagram icon.png" width="30" height="30"></a>
            </div>
        </div>
        <div class="row">
            <div class="feature-box col-lg-6 col-md-12 col-sm-12">
                <img class="portrait mb-3" src="../static/alvin_round.png">
                <h3>Alvin Audinata</h3>
                <i class="text-threefourth">1806200204 / DPTK 1-01</i>
                <p></p>
                <div class="container">
                    <div class="row">
                        <div class="col-lg-3 col-md-0 col-sm-0"></div>
                        <div class="col-lg-2 col-md-4 col-sm-4">
                            <a href="https://instagram.com/alvinaudinata"><img src="../static/Instagram icon.png" width="30" height="30"></a>
                        </div>
                        <div class="col-lg-2 col-md-4 col-sm-4">
                            <a href="https://www.facebook.com/alvin.audinata/"><img src="../static/Facebook icon.png" width="30" height="30"></a>
                        </div>
                        <div class="col-lg-2 col-md-4 col-sm-4">
                            <a href="mailto:alvin_audinata@yahoo.com"><img src="../static/Email icon.png" width="30" height="30"></a>
                        </div>
                        <div class="col-lg-3 col-md-0 col-sm-0"></div>
                    </div>
                </div>
            </div>
            <div class="feature-box col-lg-6 col-md-12 col-sm-12">
                <img class="portrait mb-3" src="../static/abraham_round.png">
                <h3>Yusuf Abraham Bimo Kristanto</h3>
                <i class="text-threefourth">1806200274 / DPTK 1-02</i>
                <p></p>
            </div>
        </div>
    </section>
    <section id="form">
        <h2 class="text-center">Contact Form</h2>
        <iframe class="block-center" src="https://docs.google.com/forms/d/e/1FAIpQLSdx0jojUFJsDKlWrkAvMHz64C_6lhIq6LTQm9FdIiH2Jg-pCw/viewform?embedded=true" width="900" height="900" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
    </section>

    <Footer />
  </div>
</template>

<script>
export default {
    head: {
        title: "Contact Us - KetahUIparkir"
    }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500;1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700&display=swap");

.body {
  scroll-behavior: smooth;
}
#title {
    background-color: #FFF;
}

#team {
    padding: 5% 5%;
    background-color: #eeec7665;
}

.members-container {
    text-align: center;
    padding: 3%;
}

#form {
    padding: 5% 15%;
    background-color: #FCECDD;
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
    font-family: "Playfair Display", sans-serif;
    font-style: italic;
    font-weight: 900;
    font-size: 3.5rem;
    line-height: 1.5;
}

h2 {
    font-family: "Nunito", sans-serif;
    font-size: 3rem;
    line-height: 1.5;
}

h3 {
    font-family: "Nunito", sans-serif;
    font-size: 1.5rem;
}

p {
    color: #8f8f8f;
}

.text-center {
    text-align: center;
}

.text-threefourth {
    font-size: 0.75em;
}

.portrait {
    max-height: 300px;
}

.block-center {
    display: block !important;
    margin: 0 auto;
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
    color: #000 !important;
}

.nav-link {
    font-size:1.25rem;
    color: #000 !important;
}

.nav-font {
  font-family: "Nunito";
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