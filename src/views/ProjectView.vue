<template>
  <section id="Projects" class="bg-dark text-light min-vh-100">
    <div class="container project-box">
      <div class="header">
        <h2>
          My
          <span class="text-success">Projects</span>
        </h2>
      </div>
      <div class="container">
        <div class="row project-holder">
          <div v-for="project_card in project_card" :key="project_card.id">
            <!-- <div class="col"> -->
            <div class="project">
              <img class="img-fluid" :src="project_card.img" />
              <div class="project-details">
                <div id="project1" class="bg-dark"></div>
                <div class="header-project-box">
                  <h3>{{ project_card.project_Label }}</h3>
                  <p>{{ project_card.project_name }}</p>
                  <div class="modal-footer">
                    <a
                      :href="project_card.github"
                      target="_blank"
                      class="btn btn-secondary"
                      ><i class="fa-brands fa-github github-icon-project"></i
                    ></a>
                    <a
                      :href="project_card.netlify"
                      target="_blank"
                      class="btn btn-primary"
                    >
                      <img
                        class="netlify-icon"
                        src="https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/4691413_netlify_icon.png?raw=true"
                      />
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="line-projects"></div>
    <!-- </div> -->
  </section>
</template>
<script>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  data() {
    return {
      project_card: [
        {
          id: "1",
          img: "https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/calc.jpg?raw=true",

          project_Label: "Project-1",
          project_name: "Calculator",
          github: "https://github.com/AbuBakrKhan24/Calculator.git",
          netlify: "https://celebrated-hamster-185d7b.netlify.app",
          project_desc:
            "This was a project where I made a calculator template, this was done using HTML and CSS. It is not functional as I have not added any JavaScript to make the calculator work.",
        },
        {
          id: "2",
          img: "https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/group.jpg?raw=true",

          github: "https://github.com/AbuBakrKhan24/Project_1.git",
          netlify: "https://comfy-axolotl-4c4a89.netlify.app",
          project_desc: "Restaurant Website",
          project_Label: "Project-2",
          project_name: "Restaurant Website",
        },
        {
          id: "3",
          img: "https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/holi.jpg?raw=true",

          github: "https://github.com/AbuBakrKhan24/holiday_destination.git",
          netlify: "https://incandescent-sable-1e2675.netlify.app",
          project_desc:
            "This was a website I made that would be used for people to contact a call center via email to book a holiday for themselves or their families. I used HTML and CSS for this to work.",
          project_Label: "Project-3",
          project_name: " Holiday Destination",
        },
        {
          id: "4",
          img: "https://github.com/AbuBakrKhan24/Main_Project_Portfolio/blob/main/Resources/Images/personal.jpg?raw=true",
          github: "https://github.com/AbuBakrKhan24/Personal_Portfolio.git",
          netlify: "https://merry-sundae-6ab06d.netlify.app",
          project_desc:
            "This was the first portfolio I made which was a mock portfolio for the academy I went to and I used a template of another person for guidance. I used HTML, CSS, and Bootstrap.",
          project_Label: "Project-4",
          project_name: " Portfolio Project",
        },
        {
          id: "5",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62951849f18120156c83a604/screenshot_2022-05-30-19-17-37-0000.png",
          github: "https://github.com/AbuBakrKhan24/FCC_CatPhotoApp.git",
          netlify: "https://willowy-douhua-c9589f.netlify.app",
          project_desc:
            "This project I made from the course I took on FreeCodeCamp I had to make a cat photo app with the resources that was given to me on there website. I used HTML for this project.",
          project_Label: "Project-5",
          project_name: " CatPhoto App",
        },
        {
          id: "6",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/6298e9970b14d103de61e247/screenshot_2022-06-02-16-47-27-0000.png",
          github: "https://github.com/AbuBakrKhan24/FCC_CafeMenu.git",
          netlify: "https://superb-cupcake-0596ac.netlify.app",
          project_desc:
            "This project I made from the course I took on FreeCodeCamp I had to make a Coffee menu with the resources that was given to me on there website. I used HTML and CSS for this project.",
          project_Label: "Project-6",
          project_name: " Cafe Menu",
        },
        {
          id: "7",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62a0d2c51152ff00afc4e41e/screenshot_2022-06-08-16-48-12-0000.png",
          github:
            "https://github.com/AbuBakrKhan24/FCC_Set_of_Colored_Markers.git",
          netlify: "https://heroic-biscotti-58cf9d.netlify.app",
          project_desc:
            "This project I made from the course I took on FreeCodeCamp I had to make Color Markers with the resources that was given to me on there website. I used HTML and CSS for this project.",
          project_Label: "Project-7",
          project_name: "CSS Color Marker ",
        },
        {
          id: "8",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62a37cf66f7443752ce7c22b/screenshot_2022-06-10-17-18-54-0000.png",
          github: "https://github.com/AbuBakrKhan24/FCC_Registration_Form.git",
          netlify: "https://silly-palmier-1fcbe5.netlify.app",
          project_desc:
            "This project I made from the course I took on FreeCodeCamp I had to make a Register Form with the resources that was given to me on there website. I used HTML and CSS for this project.",
          project_Label: "Project-8",
          project_name: " Register Form",
        },
        {
          id: "9",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62a9e392ec42760008cb3f6a/screenshot_2022-06-15-13-50-17-0000.png",
          github: "https://github.com/AbuBakrKhan24/BMI_Calculator.git",
          netlify: "https://heartfelt-treacle-9e3359.netlify.app",
          project_desc:
            "This project I made from the course I took at LifeChoices Academy I had to make a BMI Calculator. I used HTML, CSS and JavaScript for this project.",
          project_Label: "Project-9",
          project_name: "BMI Calculator",
        },
        {
          id: "10",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62a9b33580ed7b0008f7caa9/screenshot_2022-06-15-10-23-57-0000.png",
          github: "https://github.com/AbuBakrKhan24/Temperature_Convertor.git",
          netlify: "https://spontaneous-licorice-f35a96.netlify.app",
          project_desc:
            "This project I made from the course I took at LifeChoices Academy I had to make a Temperature Convertor. I used HTML, CSS and JavaScript for this project.",
          project_Label: "Project-10",
          project_name: "Temperature Convertor ",
        },
        {
          id: "11",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62a9ff8a651ff14609007f49/screenshot_2022-06-15-15-49-41-0000.png",
          github: "https://github.com/AbuBakrKhan24/FCC_Rothko_Painting.git",
          netlify: "https://sensational-elf-d20cd7.netlify.app",
          project_desc:
            "This project I made from the course I took on FreeCodeCamp I had to make a Rothko Painting. I used HTML and CSS for this project.",
          project_Label: "Project-11",
          project_name: "Rothko Painting",
        },
        {
          id: "12",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62b49c4c7ed223023cd381ab/screenshot_2022-06-23-17-01-07-0000.png",
          github:
            "https://github.com/AbuBakrKhan24/FCC_Typography_Nutrition_Label.git",
          netlify: "https://eclectic-kelpie-31ffa3.netlify.app",
          project_desc:
            "This project I made from the course I took on FreeCodeCamp I had to make a Typography Nutrition Label. I used HTML and CSS for this project.",
          project_Label: "Project-12",
          project_name: "Typography Nutrition Label",
        },
        {
          id: "13",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62b77b8e6f868200087a6a41/screenshot_2022-06-25-21-18-13-0000.png",
          github: "https://github.com/AbuBakrKhan24/ToDo_App.git",
          netlify: "https://thriving-pudding-8e9628.netlify.app",
          project_desc:
            "This project I made from the course I took at LifeChoices Academy I had to make a To Do App. I used HTML, CSS and JavaScript for this project.",
          project_Label: "Project-13",
          project_name: "To Do App",
        },
        {
          id: "14",
          img: "https://screenshot-proxy.netlify.app/f_avif,w_336/https://d33wubrfki0l68.cloudfront.net/62bf1c660ac02c000912478e/screenshot_2022-07-01-16-10-22-0000.png",
          github: "https://github.com/AbuBakrKhan24/JS_Project.git",
          netlify: "https://playful-sopapillas-9f6cd3.netlify.app",
          project_desc:
            "This project I made from the course I took at LifeChoices Academy I had to make a Property Site . I used HTML, CSS and JavaScript for this project.",
          project_Label: "Project-14",
          project_name: "Property Site",
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
<style scoped>
/* Project */

section#Projects {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 6%;
}

.header {
  display: flex;
  justify-content: center;
  padding-bottom: 30px;
}
#testY {
  display: flex;
  flex-wrap: wrap;
}

.project {
  position: relative;
  /* width: 25%; */
}
.row .project-holder {
  display: flex;
  flex-wrap: wrap;
}

.project-details {
  background: #212529;
  color: white;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 30px;
  display: flex;
  flex-direction: column;
  justify-content: end;
  opacity: 0;
  transition: all 0.3s linear;
}

.project:hover .project-details {
  opacity: 1;
  border: 3px #198754 solid;
}

/* .header-project-box {
  display: flex;
  justify-content: center;
  padding-bottom: 80px;
  padding-left: 120px;
  position: absolute;
  flex-direction: column;
} */
.header-project-box[data-v-3e99fe14][data-v-3e99fe14] {
  display: flex;
  width: 80%;
  justify-content: center;
  position: absolute;
  flex-direction: column;
}

.project-card {
  padding-top: 10px;
  padding-bottom: 10px;
  width: 24vw !important;
}

.project img {
  object-fit: cover;
  width: 100%;
}

.project-holder {
  display: flex;
  flex-direction: row;
  justify-content: center;
}

#project1 {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
#project2 {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
#project3 {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
#project4 {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

.line-projects {
  margin-top: 5%;
  margin-bottom: 9%;
  border-top: solid 2px #08d665;
}

.github-icon-project {
  color: #fff;
}

.netlify-icon {
  vertical-align: middle;
  object-fit: cover;
  height: 20px;
  width: 100%;
  padding-bottom: 3px;
}

.modal-footer {
  justify-content: space-evenly;
  border-top: 1px solid #198754;
}

.modal-header {
  border-bottom: 1px solid #198754;
}

.btn-primary:hover {
  color: #fff;
  background-color: #0dcaf0;
  border-color: #0a58ca;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #212529;
  border-color: #565e64;
}

i.fa-brands.fa-github.github-icon-project {
  font-size: large;
}

.modal-footer {
  justify-content: space-evenly;
  border-top: 1px solid #198754;
  padding-top: 10%;
}
/* project done */

.row {
  flex-shrink: 0;
  width: 33%;
  max-width: 100%;
  padding-right: calc(var(--bs-gutter-x) * 0.5);
  padding-left: calc(var(--bs-gutter-x) * 0.5);
  padding-bottom: calc(var(--bs-gutter-x) * 0.5);
  margin-top: var(--bs-gutter-y);
}
.row * > {
  flex-shrink: 0;
  width: 33%;
  max-width: 100%;
  padding-right: calc(var(--bs-gutter-x) * 0.5);
  padding-left: calc(var(--bs-gutter-x) * 0.5);
  padding-bottom: calc(var(--bs-gutter-x) * 0.5);
  margin-top: var(--bs-gutter-y);
}

.row > * {
  flex-shrink: 0;
  width: 33%;
  max-width: 100%;
  padding-right: calc(var(--bs-gutter-x) * 0.5);
  padding-left: calc(var(--bs-gutter-x) * 0.5);
  padding-bottom: calc(var(--bs-gutter-x) * 0.5);
  margin-top: var(--bs-gutter-y);
}

.row > * > {
  flex-shrink: 0;
  width: 33%;
  max-width: 100%;
  padding-right: calc(var(--bs-gutter-x) * 0.5);
  padding-left: calc(var(--bs-gutter-x) * 0.5);
  padding-bottom: calc(var(--bs-gutter-x) * 0.5);
  margin-top: var(--bs-gutter-y);
}

@media screen and (max-width: 1000px) {
  .row > *[data-v-3e99fe14] {
    flex-shrink: 0;
    width: 50%;
    max-width: 100%;
    padding-right: calc(var(--bs-gutter-x) * 0.5);
    padding-left: calc(var(--bs-gutter-x) * 0.5);
    padding-bottom: calc(var(--bs-gutter-x) * 0.5);
    margin-top: var(--bs-gutter-y);
  }
}
@media screen and (max-width: 1000px) {
  .row > *[data-v-3e99fe14] {
    flex-shrink: 0;
    width: 100%;
    max-width: 100%;
    padding-right: calc(var(--bs-gutter-x) * 0.5);
    padding-left: calc(var(--bs-gutter-x) * 0.5);
    padding-bottom: calc(var(--bs-gutter-x) * 0.5);
    margin-top: var(--bs-gutter-y);
  }
}
</style>
