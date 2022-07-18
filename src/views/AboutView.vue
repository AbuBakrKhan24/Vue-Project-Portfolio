<template>
  <div>
    <Navbar />
    <section id="About" class="bg-dark text-light section_style">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <img
              class="img-fluid about_pic"
              src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/about_pic.jpg?raw=true"
            />
          </div>
          <div class="col-md-6 home_details">
            <div class="header-about">
              <h3>
                About
                <span class="text-success">Me</span>
              </h3>
            </div>
            <div class="about-info">
              <p>
                Hi, My name is Abu-Bakr. I am an aspiring Full Stack Developer.
                I really enjoy helping others and trying out new things. Always
                aim to achieve my goals and live my life to its fullest each
                day.
              </p>
              <p>
                I play lots of open-world games and try modding them to make
                them more fun to play, I try to keep it to a minimum so I make
                time for other daily activities.
              </p>
              <p>
                In my spare time, I tend to do lots of research on old
                historical events and what is happening around the world so that
                I am up to date with things happening around me.
              </p>
            </div>
            <div class="about_me_details">
              <div class="row">
                <div class="col-lg-6 col-md-12 about_me_details_cols">
                  <ul class="list-unstyled">
                    <li>
                      <span class="about_details text-light">Name:</span>
                      <span class="about_details_col1">Abu-Bakr Khan</span>
                    </li>
                    <li>
                      <span class="about_details text-light">Age:</span>
                      <span class="about_details_col1">19</span>
                    </li>
                    <li>
                      <span class="about_details text-light">Address:</span>
                      <span class="about_details_col1"
                        >Pelikan Park, South Africa</span
                      >
                    </li>
                  </ul>
                </div>
                <div class="col-lg-6 col-md-12 about_me_details_cols">
                  <ul class="list-unstyled">
                    <li>
                      <span class="about_details text-light">Phone:</span>
                      <span>(+27) 74 480 1770</span>
                    </li>
                    <li>
                      <span class="about_details text-light">E-Mail:</span>
                      <span>abubakrkhan224@gmail.com</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="line-about" id="Skills"></div>
        <div class="container">
          <div class="header">
            <h2>
              My
              <span class="text-success">Skills</span>
            </h2>
          </div>
        </div>

        <div class="container skill-content">
          <div class="row">
            <div class="col-lg-6 col-md-12 skills">
              <div class="badges">
                <i class="fa-brands fa-html5 text-danger"></i>
              </div>
              <div class="progress progress-design">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated bg-danger"
                  role="progressbar"
                  style="width: 100%"
                  aria-valuenow="100"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  100%
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-md-12 skills">
              <div class="badges">
                <i class="fa-brands fa-bootstrap text-secondary"></i>
              </div>
              <div class="progress progress-design">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated bg-secondary"
                  role="progressbar"
                  style="width: 65%"
                  aria-valuenow="65"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  65%
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-md-12 skills">
              <div class="badges">
                <i class="fa-brands fa-css3-alt text-info"></i>
              </div>
              <div class="progress progress-design">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated bg-info"
                  role="progressbar"
                  style="width: 80%"
                  aria-valuenow="80"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  80%
                </div>
              </div>
            </div>

            <div class="col-lg-6 col-md-12 skills">
              <div class="badges">
                <i class="fa-brands fa-js bg-warning text-dark"></i>
              </div>
              <div class="progress progress-design">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated bg-warning"
                  role="progressbar"
                  style="width: 100%"
                  aria-valuenow="0"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  Still Working on it ;)
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-md-12 skills">
              <div class="badges">
                <i class="fa-brands fa-vuejs text-success"></i>
              </div>
              <div class="progress progress-design">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated bg-success"
                  role="progressbar"
                  style="width: 100%"
                  aria-valuenow="70"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  Still working on it ;)
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-md-12 skills">
              <div class="badges">
                <i class="fa-brands fa-github"></i>
              </div>
              <div class="progress progress-design">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated bg-dark"
                  role="progressbar"
                  style="width: 80%"
                  aria-valuenow="80"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  80%
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="line-skills" id="Testimonials"></div>
        <div class="container Testimonials">
          <div class="header">
            <h2>
              My
              <span class="text-success">Testimonials</span>
            </h2>
          </div>
          <div
            id="carouselExampleIndicators"
            class="carousel slide"
            data-bs-ride="carousel"
          >
            <div class="carousel-indicators">
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="0"
                class="active"
                aria-current="true"
                aria-label="Slide 1"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="1"
                aria-label="Slide 2"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="2"
                aria-label="Slide 3"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="3"
                aria-label="Slide 4"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="4"
                aria-label="Slide 5"
              ></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="10000">
                <div class="row carousel-border">
                  <div class="col-lg-6">
                    <img
                      src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/jason.png?raw=true"
                      class="d-block w-100 Testimonial-pic"
                      alt="..."
                    />
                  </div>
                  <div class="col-lg-6 testimonial-details">
                    <h3>Jason Wandrag</h3>
                    <div class="price"></div>
                    <p class="fst-italic">
                      Abu-Bakr Khan brings a unique energy to my lectures. He
                      often likes to participate or help his colleagues with the
                      work whenever he can. It's always a pleasure watching him
                      co-operate with his peers. I am cheering Abu-Bakr Khan on
                      to do well in his development career.
                    </p>
                  </div>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <div class="row carousel-border">
                  <div class="col-lg-6">
                    <img
                      src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/Zoe%20(1).JPG?raw=true"
                      class="d-block w-100 Testimonial-pic"
                      alt="..."
                    />
                  </div>
                  <div class="col-lg-6 testimonial-details">
                    <h3>Zoë Van Der Schyff</h3>

                    <p class="fst-italic">
                      Abu-Bakr is amazingly talented and is determined to
                      achieve all his goals. He has many technical and soft
                      skills and makes use of them daily. He maintains focus and
                      strives to reach his full potential every day.
                    </p>
                  </div>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="3500">
                <div class="row carousel-border">
                  <div class="col-lg-6">
                    <img
                      src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/Le-Andre.png?raw=true"
                      class="d-block w-100 Testimonial-pic"
                      alt="..."
                    />
                  </div>
                  <div class="col-lg-6 testimonial-details">
                    <h3>Le-Andre Moritz</h3>

                    <p class="fst-italic">
                      Abu-Bakr is one of the most disciplined people that I have
                      ever met, He is Hardworking as well which makes for a very
                      reliable person to interact with a business sense. He is
                      amazingly kind and his open-minded mentality makes him an
                      all-around delightful person.
                    </p>
                  </div>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="2000">
                <div class="row">
                  <div class="col-lg-6">
                    <img
                      src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/Carla%20(1).JPG?raw=true"
                      class="d-block w-100 Testimonial-pic"
                      alt="..."
                    />
                  </div>
                  <div class="col-lg-6 testimonial-details">
                    <h3>Carla Lawrence</h3>

                    <p class="fst-italic">
                      Abu Bakr Khan is destined for greatness. He is a driven,
                      well skilled and focused. Any project that Abu Bakr has
                      worked on, displays both his knowledge of design and
                      functionality of web development. I have no doubt in my
                      mind that He will succeed and be an asset in any team or
                      company.
                    </p>
                  </div>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="2000">
                <div class="row">
                  <div class="col-lg-6">
                    <img
                      src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/Mika.jpg?raw=true   "
                      class="d-block w-100 Testimonial-pic"
                      alt="..."
                    />
                  </div>
                  <div class="col-lg-6 testimonial-details">
                    <h3>Mika Rinquest</h3>

                    <p class="fst-italic">
                      Abu-Bakr is a very outgoing person. Others often look to
                      him when they need help. The energy he brings with him
                      will brighten any workforce he joins.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="line-testimonials"></div>
        </div>
      </div>
    </section>
  </div>
  <Footer />
</template>
<script>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>
<style>
/* About */

section#About {
  padding-top: 10%;
}

.header-about {
  padding-bottom: 30px;
}

.about-info {
  border-bottom: 1px solid #08d665;
  margin-bottom: 13px;
}

img.about_pic {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.about_details {
  font-weight: 600;
  position: relative;
  width: 60px;
  display: inline-block;
  margin-bottom: 10px;
  color: #222;
}

.about_details_col1 {
  padding-left: 10px;
}

.line-about {
  margin-top: 10%;
  margin-bottom: 5%;
  border-top: solid 2px #08d665;
}

/* Skilss */

#Skills {
  padding-bottom: 5%;
}

.skill-content {
  display: flex;
  flex-direction: column;
}

.skills {
  display: flex;
}

.badges {
  font-size: 3pc;
  width: 20%;
  text-align: center;
}

.progress-design {
  margin-left: 20px;
  margin-top: 25px;
  width: 70%;
}

.line-skills {
  margin-top: 10%;
  margin-bottom: 5%;
  border-top: solid 2px #08d665;
}

/* Testimonials */

#Testimonials {
  padding-bottom: 5%;
}

.carousel-indicators {
  bottom: 10px;
}
.carousel-indicators [data-bs-target] {
  border-radius: 50%;
  width: 10px;
  height: 10px;
}

.carousel-inner {
  border: 2px solid #198754;
  padding: 75px;
}

.Testimonial-pic {
  height: 300px;
  object-fit: cover;
  border-radius: 20%;
  padding-bottom: 20px;
}

.testimonial-details {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.modal-pic {
  padding: 30px;
}

/* about done */
</style>
