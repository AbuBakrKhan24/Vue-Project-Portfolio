<template>
  <section id="Resume" class="resume bg-dark text-light">
      <div class="header">
        <h2>
          My
          <span class="text-success">Resume</span>
        </h2>
      </div>
    <div class="container resume_content">
      <div class="row">
        <div class="col-md-6">
          <h3 class="resume-title">Education</h3>
          <div class="resume-item">
            <h4>Grassy Park High School</h4>
            <h5>2017 - 2020</h5>
            <p><em>Secondary High School, Grassy Park, Cape Town</em></p>
            <p>
              I attended Grassy Park High School for four years as I started in
              grade nine and was a transfer student from Pelican Park High
              School. I have participated in sporting activities while attending
              the school, and always helped the teachers with setting up their
              laptops and the projectors, I was their so-called tech boy.
            </p>
          </div>
          <div class="resume-item">
            <h4>Muhammadeyah Primary School</h4>
            <h5>2009 - 2015</h5>
            <p><em>Muslim School, Wynberg, Cape Town</em></p>
            <p>
              I attended Muhammadeyah Muslim Primary School, was involved with
              sports activities for sports day, and played rugby for the school.
              I have had computer classes where we learned how to use a computer
              and how to use Microsoft Office Applications.
            </p>
          </div>
        </div>
        <div class="col-md-6">
          <h3 class="resume-title">Professional Experience</h3>
          <div class="resume-item">
            <h4>Full Stack Developer</h4>
            <h5>2022 - Present</h5>
            <p><em>Life Choices, Lansdowne, Cape Town </em></p>
            <ul class="list-unstyled">
              <li>Attending an</li>
              <li>
                Attending an academy that focuses on Front-End and Back-End
                Development, is a 12-month course broken up into the first 6
                months the learning how to code and the other 6 months is where
                we work for an internship.
              </li>
            </ul>
          </div>
          <div class="resume-item">
            <h4>Call Center Agent</h4>
            <h5>2021</h5>
            <p><em>AskOsca, Grassy Park, Cape Town</em></p>
            <ul class="list-unstyled">
              <li>
                Worked at a call center company called AskOsca for a leadership
                that was for 12 months, I have learned how to deal with speaking
                to people from different companies professionally.
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="line-resume"></div>
    </div>
  </section>
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
/* Resume */


section#Resume {
      display: flex;
    min-height: 92vh;
    flex-direction: column;
    justify-content: center;
}

.resume_content {
  text-align: justify;
}

.resume .resume-item {
  padding: 0 0 20px 20px;
  margin-top: -2px;
  border-left: 2px solid #08d665;
  position: relative;
}

.resume .resume-item::before {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  border-radius: 50px;
  left: -9px;
  top: 0;
  background: #fff;
  border: 2px solid #08d665;
}
/* 
.line-resume {
 
  padding-top: 5px;
  border-top: solid 2px #08d665;
} */

/* resume done */
</style>
