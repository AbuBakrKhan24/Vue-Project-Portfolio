<template>
  <Navbar />
  <section id="Contact" class="bg-dark text-light">
    <div class="container">
      <div class="header-contact">
        <h2>
          CONTACT
          <span class="text-success">ME</span>
        </h2>
      </div>
      <form action="https://formspree.io/f/mzbojdwq" method="POST">
        <div class="row">
          <div class="col-md-6">
            <div class="contact_input">
              <input
                type="text"
                class="form-control bg-dark text-light"
                id="formGroupExampleInput"
                placeholder="Full Name"
              />
              <div class="row">
                <div class="col mt-3">
                  <input
                    type="text"
                    class="form-control bg-dark text-light"
                    placeholder="Email"
                    aria-label="Email"
                  />
                </div>
                <div class="col mt-3">
                  <input
                    type="text"
                    class="form-control bg-dark text-light"
                    placeholder="Subject"
                    aria-label="Subject"
                  />
                </div>
              </div>
              <textarea
                rows="5"
                name="message"
                class="form-control bg-dark text-light mt-3"
                placeholder="Your Message"
                required="required"
              ></textarea>
            </div>
            <div class="sub-button mt-3">
              <input type="submit" value="Send message" />
            </div>
          </div>
          <div class="col-md-6">
            <div class="row contact-box-details">
              <div class="contact_details border border-white">
                <h6>CONTACT ADDRESS</h6>
                <div class="container contact_icons">
                  <div class="col contact_info">
                    <div class="contact_icon_info">
                      <i class="fa-solid fa-location-dot"> </i>
                    </div>
                    <div class="details">
                      <p>Pelikan Park</p>
                    </div>
                  </div>
                  <div class="col contact_info">
                    <div class="contact_icon_info">
                      <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div class="details">
                      <p>abubakrkhan224@gmail.com</p>
                    </div>
                  </div>
                  <div class="col contact_info">
                    <div class="contact_icon_info">
                      <i class="fa-solid fa-phone"></i>
                    </div>
                    <div class="details">
                      <p>(+27) 74 480 1770</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </form>
    </div>
  </section>
  <!-- <section id="Contact" class="bg-dark text-light">
    <div class="container">
      <div class="section-title">
        <h2>Contact</h2>
        <p>
          Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex
          aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos
          quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia
          fugiat sit in iste officiis commodi quidem hic quas.
        </p>
      </div>
      <div class="row">
        <div class="col-lg-5 d-flex align-items-stretch">
          <div class="info">
            <div class="address">
              <i class="fa-solid fa-location-dot"></i>
              <h4>Location:</h4>
              <p>A108 Adam Street, New York, NY 535022</p>
            </div>
            <div class="email">
              <i class="fa-solid fa-envelope"></i>
              <h4>Email:</h4>
              <p>abubakrkhan224@gmail.com</p>
            </div>
            <div class="phone">
              <i class="fa-solid fa-mobile-screen"></i>
              <h4>Call:</h4>
              <p>+27 74 480 1770</p>
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3308.267419708809!2d18.49050991516957!3d-33.98566428062407!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc433bedd50e81%3A0x9c746d268c8e0ad9!2sLife%20Choices!5e0!3m2!1sen!2sza!4v1651239149199!5m2!1sen!2sza"
                width="600"
                height="450"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>
        </div>
        <div class="col-lg-7 mt-5 mt-lg-0 d-flex align-items-stretch">
          <form
            action="https://formspree.io/f/mzbojdwq"
            method="post"
            role="form"
            class="php-email-form"
          >
            <div class="row">
              <div class="form-group col-md-6">
                <label for="name">Your Name</label>
                <input
                  type="text"
                  name="name"
                  class="form-control"
                  id="name"
                  required=""
                />
              </div>
              <div class="form-group col-md-6">
                <label for="name">Your Email</label>
                <input
                  type="email"
                  class="form-control"
                  name="email"
                  id="email"
                  required=""
                />
              </div>
            </div>
            <div class="form-group">
              <label for="name">Subject</label>
              <input
                type="text"
                class="form-control"
                name="subject"
                id="subject"
                required=""
              />
            </div>
            <div class="form-group">
              <label for="name">Message</label>
              <textarea
                class="form-control"
                name="message"
                rows="10"
                required=""
              ></textarea>
            </div>
            <div class="my-3">
              <div class="loading">Loading</div>
              <div class="error-message"></div>
              <div class="sent-message">
                Your message has been sent. Thank you!
              </div>
            </div>
            <div class="text-center">
              <input type="submit" value="Submit" />
            </div>
          </form>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="header-contact">
        <h2>
          CONTACT
          <span class="text-success">ME</span>
        </h2>
      </div>
      <form action="https://formspree.io/f/mzbojdwq" method="POST">
        <div class="row">
          <div class="col-md-6">
            <div class="contact_input">
              <input
                type="text"
                class="form-control bg-dark text-light"
                id="formGroupExampleInput"
                placeholder="Full Name"
              />
              <div class="row">
                <div class="col mt-3">
                  <input
                    type="text"
                    class="form-control bg-dark text-light"
                    placeholder="Email"
                    aria-label="Email"
                  />
                </div>
                <div class="col mt-3">
                  <input
                    type="text"
                    class="form-control bg-dark text-light"
                    placeholder="Subject"
                    aria-label="Subject"
                  />
                </div>
              </div>
              <textarea
                rows="5"
                name="message"
                class="form-control bg-dark text-light mt-3"
                placeholder="Your Message"
                required="required"
              ></textarea>
            </div>
            <div class="sub-button mt-3">
              <input type="submit" value="Send message" />
            </div>
          </div>
          <div class="col-md-6">
            <div class="row contact-box-details">
              <div class="contact_details border border-white">
                <h6>CONTACT ADDRESS</h6>
                <div class="container contact_icons">
                  <div class="col contact_info">
                    <div class="contact_icon_info">
                      <i class="fa-solid fa-location-dot"> </i>
                    </div>
                    <div class="details">
                      <p>Pelikan Park</p>
                    </div>
                  </div>
                  <div class="col contact_info">
                    <div class="contact_icon_info">
                      <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div class="details">
                      <p>abubakrkhan224@gmail.com</p>
                    </div>
                  </div>
                  <div class="col contact_info">
                    <div class="contact_icon_info">
                      <i class="fa-solid fa-phone"></i>
                    </div>
                    <div class="details">
                      <p>(+27) 74 480 1770</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </form>
    </div>
  </section> -->
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
/* contact */

section#Contact {
  padding-top: 5%;
  padding-bottom: 7%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.header-contact {
  display: flex;
  justify-content: center;
  padding-bottom: 60px;
}

.contact_details {
  width: 100%;
  height: 300px;
}

.sub-button {
  display: flex;
  justify-content: center;
  margin-bottom: 15px;
}

input[type="submit"] {
  border-radius: 30px;
  padding: 10px 20px;
  background: darkslategrey;
  color: #fff;
  border: #08d665;
}

input[type="submit"]:hover {
  background: #08d665;
  border: #08d665;
  transition: 0.5s;
}

.form-control:focus {
  color: #212529;
  background-color: #fff;
  border-color: rgb(8 214 101);
  outline: 0;
  box-shadow: 0 0 0 -0.85rem rgb(8 214 101);
}

.contact_details {
  padding-left: 20px;
}

.contact_details h6 {
  margin-top: 20px;
  margin-bottom: 25px;
}

.contact_icons i {
  padding-left: 0%;
}
.contact_icons i {
  display: flex;
  justify-content: space-between;
  font-size: 20px;
  background: #08d665;
  color: #fff;
  padding-top: 15px;
  padding-left: 15px;
  margin-bottom: 25px;
  border-radius: 50%;
  width: 50px;
  height: 50px;
}

.contact_info {
  display: flex;
}

.details {
  display: flex;
  padding-left: 15px;
  padding-bottom: 15px;
  flex-direction: column;
  justify-content: center;
}

.contact-boc-details {
  margin: 0px;
}
</style>
