<template>
    <div class="About">
    <div class="page-header d-flex align-items-center">
      <div class="container position-relative">
        <div class="row d-flex justify-content-center">
          <div class="col-lg-6 text-center">
            <h2>About</h2>
            <p>A photography website is a platform to showcase work, tell stories, and connect with an audience, 
                using high-quality images and clear navigation.</p>
          </div>
        </div>
      </div>
    </div><!-- End Page Header -->

    <!-- ======= About Section ======= -->
    <section id="about" class="about">
      <div class="container">

        <div class="row gy-4 justify-content-center">
          <div class="col-lg-4">
            <img src="../assets/daryll.jpg" class="img-fluid" alt="">
          </div>
          <div class="col-lg-5 content">
            <h2>Photographer from Philippines</h2>
            <div class="row">
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Birthday:</strong> <span>1 May 1995</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Website:</strong> <span>therealtravelblog</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Phone:</strong> <span>0954-541-4182</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>City:</strong> <span>Pampanga, Philippines</span></li>
                </ul>
              </div>
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Age:</strong> <span>20</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Degree:</strong> <span>Web Dev</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Section:</strong> <span>WD - 201</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Email</strong> <span>daryllmedina@gmail.com</span></li>
                </ul>
              </div>
            </div>
            <p class="py-3">
              Photography is a powerful tool for self-expression, storytelling, and capturing the beauty of the world around us. It allows us to freeze moments in time, 
              immortalizing memories that we can revisit and share with others for years to come. Photography also offers us a unique perspective on the world, enabling us 
              to see things in a new light and appreciate the intricacies and details of our surroundings. By picking up a camera and exploring the art of photography, 
              we can develop our creativity, expand our horizons, and discover new passions. Whether you're looking to document your travels, 
              express your artistic vision, or simply capture the beauty of everyday life, photography can provide you with a fulfilling and rewarding experience.
            </p>
          </div>
        </div>

      </div>
    </section><!-- End About Section -->
    </div>
</template>

<script>
export default {
    name: 'About',
    data(){
        return{
            title:'This is the About Component'
        }
    }
}
</script>
<style>
.about .content h2 {
  font-weight: 700;
  font-size: 24px;
  color: var(--color-primary);
}

.about .content ul {
  list-style: none;
  padding: 0;
}

.about .content ul li {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}

.about .content ul strong {
  margin-right: 10px;
}

.about .content ul i {
  font-size: 16px;
  margin-right: 5px;
  color: var(--color-primary);
  line-height: 0;
}

h2 , p {
    color: #fff;
}
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