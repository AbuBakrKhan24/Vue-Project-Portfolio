<template>
  <div>
    <Navbar />
    <section id="About" class="bg-dark text-light section_style">
      <div class="container">
        <div class="header">
          <h2>
            About
            <span class="text-success">Me</span>
          </h2>
        </div>
        <div class="row">
          <div class="col-lg-6 col-md-12">
            <img
              class="img-fluid about_pic"
              src="https://scontent-cpt1-1.xx.fbcdn.net/v/t39.30808-6/290757584_5550234915000228_8585479001536840644_n.jpg?
              _nc_cat=111&ccb=1-7&_nc_sid=9267fe&_nc_aid=0&_nc_ohc=FglWmzrWx54AX-g0XXA&_nc_ht=scontent-cpt1-1.xx&oh=00_AT827mugvhgYiHum8wyoB7J956vJ3foVt7uvuTnbPlVZ4w&oe=62DBB552"
            />
          </div>
          <div class="col-lg-6 col-md-12 home_details">
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
                <div class="col-lg-12 about_me_details_cols">
                  <table class="table text-light">
                    <tbody>
                      <tr>
                        <th scope="row">Full Name:</th>
                        <td>Abu-Bakr Khan</td>
                      </tr>
                      <tr>
                        <th scope="row">Age :</th>
                        <td>19</td>
                      </tr>
                      <tr>
                        <th scope="row">Location:</th>
                        <td>Pelikan Park, South Africa</td>
                      </tr>
                      <tr>
                        <th scope="row">Phone:</th>
                        <td colspan="2">074 480 1770</td>
                      </tr>
                      <tr>
                        <th scope="row">email:</th>
                        <td colspan="2">abubakrkhan224@gmail.com</td>
                      </tr>
                    </tbody>
                  </table>
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
          <div class="skills">
            <!-- HTML BADGE -->
            <div class="badge_box">
              <div class="content">
                <div class="html_front">
                  <i class="fa-brands fa-html5"></i>
                </div>
                <div class="html_back back">
                  <span class="badge_name">HTML</span>
                  <i class="fa-brands fa-html5"></i>
                </div>
              </div>
            </div>

            <!-- Bootstrap Badge -->
            <div class="badge_box">
              <div class="content">
                <div class="bootstrap_front">
                  <i class="fa-brands fa-bootstrap"></i>
                </div>
                <div class="bootstrap_back back">
                  <span class="badge_name">BOOTSTRAP</span>
                  <i class="fa-brands fa-bootstrap"></i>
                </div>
              </div>
            </div>

            <!-- CSS Badge -->
            <div class="badge_box">
              <div class="content">
                <div class="css3_front">
                  <i class="fa-brands fa-css3-alt"></i>
                </div>
                <div class="css3_back back">
                  <span class="badge_name">css</span>
                  <i class="fa-brands fa-css3-alt"></i>
                </div>
              </div>
            </div>

            <!-- JavaScript Badge -->
            <div class="badge_box">
              <div class="content">
                <div class="js_front">
                  <i class="fa-brands fa-js"></i>
                </div>
                <div class="js_back back">
                  <span class="badge_name">JavaScript</span>
                  <i class="fa-brands fa-js"></i>
                </div>
              </div>
            </div>

            <!-- Vue3 Badge -->
            <div class="badge_box">
              <div class="content">
                <div class="vuejs_front">
                  <i class="fa-brands fa-vuejs"></i>
                </div>
                <div class="vuejs_back back">
                  <span class="badge_name">VueJs</span>
                  <i class="fa-brands fa-vuejs"></i>
                </div>
              </div>
            </div>

            <!-- GitHub Badge -->
            <div class="badge_box">
              <div class="content">
                <div class="github_front">
                  <i class="fa-brands fa-brands fa-github"></i>
                </div>
                <div class="github_back back">
                  <span class="badge_name">GitHub</span>
                  <i class="fa-brands fa-brands fa-github"></i>
                </div>
              </div>
            </div>

            <!-- Databases badge -->
            <div class="badge_box">
              <div class="content">
                <div class="database_front">
                  <i class="fa-solid fa-database"></i>
                </div>
                <div class="database_back back">
                  <span class="badge_name">MySQL Database</span>
                  <i class="fa-solid fa-database"></i>
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
                      class="d-block Testimonial-pic"
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
                      class="d-block Testimonial-pic"
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
                      src="https://github.com/AbuBakrKhan24/Vue-Project-Portfolio/blob/main/pics/Leandre%20(5)1.JPG?raw=true"
                      class="d-block Testimonial-pic"
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
                      class="d-block Testimonial-pic"
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
                      class="d-block Testimonial-pic"
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
/* The Styles for this Vue file is stored in assets called About.css and is imported from main*/
</style>
