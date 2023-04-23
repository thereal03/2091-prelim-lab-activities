<template>
  <div class="Home">
  <section id="hero" class="hero d-flex flex-column justify-content-center align-items-center" data-aos="fade" data-aos-delay="1500">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6 text-center">
          <h2>I'm <span>Daryll Medina</span> a Photographer from Philippines</h2>
          <p>Welcome to the world of nature photography!<br> As a photographer, you have a unique opportunity to capture the beauty and wonder of the natural world through your lens.<br> Whether you are drawn to the grandeur of majestic mountains, the peacefulness of a calm lake, or the intricate details of a delicate flower, nature provides an endless source of inspiration for your art.<br> With your camera in hand, you can explore the vast landscapes and hidden corners of our planet, and share your vision with the world.<br> So, let's embark on a journey together, and discover the magic of nature photography!</p>
        </div>
      </div>
    </div>
  </section><!-- End Hero Section -->
    <main id="main" data-aos="fade" data-aos-delay="1500">

    <!-- ======= Gallery Section ======= -->
    <section id="gallery" class="gallery">
      <div class="container-fluid">

        <div class="row gy-4 justify-content-center">
          <div class="col-xl-3 col-lg-4 col-md-6">
            <div class="gallery-item h-100">
              <img src="../assets/gallery-1.jpg" class="img-fluid" alt="">
              <div class="gallery-links d-flex align-items-center justify-content-center">
                <a href="../assets/gallery-1.jpg" title="Gallery 1" class="glightbox preview-link"><i class="bi bi-arrows-angle-expand"></i></a>
                <a href="gallery-single.html" class="details-link"><i class="bi bi-link-45deg"></i></a>
              </div>
            </div>
          </div><!-- End Gallery Item -->
          <div class="col-xl-3 col-lg-4 col-md-6">
            <div class="gallery-item h-100">
              <img src="../assets/gallery-2.jpg" class="img-fluid" alt="">
              <div class="gallery-links d-flex align-items-center justify-content-center">
                <a href="../assets/gallery-2.jpg" title="Gallery 2" class="glightbox preview-link"><i class="bi bi-arrows-angle-expand"></i></a>
                <a href="gallery-single.html" class="details-link"><i class="bi bi-link-45deg"></i></a>
              </div>
            </div>
          </div><!-- End Gallery Item -->
          <div class="col-xl-3 col-lg-4 col-md-6">
            <div class="gallery-item h-100">
              <img src="../assets/gallery-5.jpg" class="img-fluid" alt="">
              <div class="gallery-links d-flex align-items-center justify-content-center">
                <a href="../assets/gallery-5  .jpg" title="Gallery 3" class="glightbox preview-link"><i class="bi bi-arrows-angle-expand"></i></a>
                <a href="gallery-single.html" class="details-link"><i class="bi bi-link-45deg"></i></a>
              </div>
            </div>
          </div><!-- End Gallery Item -->
          <div class="col-xl-3 col-lg-4 col-md-6">
            <div class="gallery-item h-100">
              <img src="../assets/gallery-4.jpg" class="img-fluid" alt="">
              <div class="gallery-links d-flex align-items-center justify-content-center">
                <a href="../assets/gallery-4.jpg" title="Gallery 4" class="glightbox preview-link"><i class="bi bi-arrows-angle-expand"></i></a>
                <a href="gallery-single.html" class="details-link"><i class="bi bi-link-45deg"></i></a>
              </div>
            </div>
          </div><!-- End Gallery Item -->

        </div>

      </div>
    </section><!-- End Gallery Section -->

  </main><!-- End #main -->
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data(){
      return{
          title:'This is the Home Component'
      }
  }
}
</script>
<style>
body{
  background-color: black;
}
.hero {
  width: 100%;
  min-height: 30vh;
  background: #000;
  background-size: cover;
  position: relative;
  padding: 140px 0 60px 0;
}

.hero h2 {
  margin: 0 0 10px 0;
  font-size: 38px;
  font-weight: 700;
  color: #fff;
  font-family: var(--font-secondary);
}

.hero h2 span {
  position: relative;
  z-index: 1;
  padding: 0 5px;
  display: inline-block;
}

.hero h2 span:before {
  content: "";
  position: absolute;
  height: 50%;
  bottom: 0;
  left: 0;
  right: 0;
  background: var(--color-primary);
  z-index: -1;
}

.hero p {
  color: rgba(255, 255, 255, 0.6);
  margin-bottom: 30px;
  font-size: 18px;
}

.hero .btn-get-started {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 14px;
  display: inline-block;
  padding: 12px 40px;
  border-radius: 4px;
  letter-spacing: 1px;
  text-transform: uppercase;
  transition: 0.3s;
  color: #fff;
  background: var(--color-primary);
}

.hero .btn-get-started:hover {
  background: #2cbc85;
}

@media (max-width: 768px) {
  .hero h2 {
    font-size: 32px;
  }
}
</style>