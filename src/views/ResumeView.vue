<template>
  <section id="Resume" class="resume bg-dark text-light">
    <div class="container">
      <div class="header">
        <h2>
          My
          <span class="text-success">Resume</span>
        </h2>
      </div>
      <div class="container resume_content">
        <div class="row resume_row">
          <div class="col-md-6">
            <h3 class="resume-title">Education</h3>
            <div v-for="resume in resume" :key="resume.id">
              <div class="resume-item">
                <!-- <h4>Grassy Park High School</h4> -->
                <h4>{{ resume.name_place }}</h4>
                <h5>{{ resume.year }}</h5>
                <p>
                  <em>{{ resume.place_info }}</em>
                </p>
                <p>{{ resume.desc }}</p>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <h3 class="resume-title">Professional Experience</h3>
            <div v-for="resume2 in resume2" :key="resume2.id">
              <div class="resume-item">
                <!-- <h4>Grassy Park High School</h4> -->
                <h4>{{ resume2.name_place }}</h4>
                <h5>{{ resume2.year }}</h5>
                <p>
                  <em>{{ resume2.place_info }}</em>
                </p>
                <p>{{ resume2.desc }}</p>
              </div>
            </div>
          </div>
        </div>
        <div class="line-resume"></div>
      </div>
    </div>
  </section>
</template>
<script>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  data() {
    return {
      resume: [
        {
          id: "1",
          name_place: "Grassy Park High School",
          year: "2017 - 2020",
          place_info: "Secondary High School, Grassy Park, Cape Town",
          desc: "I attended Grassy Park High School for four years as I started in grade nine and was a transfer student from Pelican Park High School. I have participated in sporting activities while attending the school, and always helped the teachers with setting up their laptops and the projectors, I was their so-called tech boy.",
        },
        {
          id: "2",
          name_place: "Muhammadeyah Primary School",
          year: "2009 - 2015",
          place_info: "Muslim School, Wynberg, Cape Town",
          desc: "I attended Muhammadeyah Muslim Primary School, was involved with sports activities for sports day, and played rugby for the school. I have had computer classes where we learned how to use a computer and how to use Microsoft Office Applications.",
        },
      ],
      resume2: [
        {
          id: "1",
          name_place: "Aspiring Full Stack Developer",
          year: "2022 - Present",
          place_info: "Life Choices, Lansdowne, Cape Town",
          desc: "Attending an academy that focuses on Front-End and Back-End Development, is a 12-month course broken up into the first 6 months the learning how to code and the other 6 months is where we work for an internship.",
        },
        {
          id: "2",
          name_place: "Call Center Agent",
          year: "2021",
          place_info: "AskOsca, Grassy Park, Cape Town",
          desc: "Worked at a call center company called AskOsca for a leadership that was for 12 months, I have learned how to deal with speaking to people from different companies professionally.",
        },
      ],
    };
  },

  components: {
    Navbar,
    Footer,
  },
};
</script>
<style>
/* Resume */
.resume_row {
  padding-top: 6%;
}

section#Resume {
  display: flex;
  min-height: 92vh;
  flex-direction: column;
  padding-top: 6%;
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
