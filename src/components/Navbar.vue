<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"></a>
        <!-- <img class="nav-badge d-none-sm" src="./Resources/Images/me_png.png" /> -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav nav-sections me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/"
                >Home</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about">About</router-link>
            </li>

            <li class="nav-item">
              <router-link class="nav-link" to="/resume">Resume</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/project">Projects</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact">Contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "Navbar",
};
</script>
<style>
/* nav */
nav.navbar {
  position: fixed;
  width: -webkit-fill-available;
  z-index: 100;
  border-bottom: #198754 1px solid;
}

.nav-badge {
  position: fixed;
  object-fit: cover;
  width: 5%;
}

.nav-sections {
  display: flex;
  width: 100%;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #212529;
  flex-direction: column;
  align-content: center;
}

.nav-item {
  display: flex;
  justify-content: end;
}

a.navbar-brand {
  padding-left: 20px;
}
.navbar-dark .navbar-nav .nav-link:hover {
  color: #ffffff;
  background: #198754;
  /* border-radius: 15%; */
  transition: 0.5s;
}

/* nav done */

@media screen and (max-width: 1000px) {
  nav.navbar {
    width: 0;
    left: 0%;
    z-index: 100;
  }
}
</style>
