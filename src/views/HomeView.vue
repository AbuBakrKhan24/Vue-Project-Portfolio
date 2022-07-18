<template>
  <Navbar />
  <section id="Home" class="text-light section_style">
    <div id="homepage" class="bg-dark"></div>
    <div class="container home-info">
      <div class="row">
        <div class="col-lg-6 home_details">
          <h5 class="text-success">HI THERE,</h5>
          <h2>I AM AN ASPIRING FULL STACK DEVELOPER</h2>
        </div>
        <div class="col-lg-6">
          <img
            class="img-fluid me"
            src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/me.1.png?raw=true"
          />
        </div>
      </div>
    </div>
  </section>

  <Footer />
</template>

<script>
// @ is an alias to /src

import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style scoped>
/* all */
section.section_style {
  display: flex;
  flex-direction: column;
  justify-content: center;
  /* padding-top: 60px; */
  /* padding-bottom: 30px; */
}
/* all done */

/* Div homepage */
#homepage {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: -1;
}
/* Div homepage done */

/* Home page section */
/* Home */

section#Home {
  padding-top: 5%;
  position: relative;
  height: 89vh;
}

.home-info {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.home_details {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 30px;
  text-shadow: 4px 4px 3px black;
}

img.me {
  width: 100%;
  height: 100%;
  -webkit-filter: drop-shadow(10px 10px 10px #222);
  filter: drop-shadow(8px 8px 5px #222);
}
/* Home done */
/* Footer */
.footer-area {
  padding-top: 7px;
  padding-bottom: 20px;
}
/* Home page section done */
</style>
