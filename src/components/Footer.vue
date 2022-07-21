<template>
  <footer class="bg-dark text-light footer-area">
    
      <div class="links">
        <a target="_blank" href="https://www.linkedin.com/in/abu-bakr-khan-a58b23225/overlay/contact-info/">
        <i class="fa-brands fa-linkedin"></i>
        </a>
        <a target="_blank" href="https://github.com/AbuBakrKhan24">
        <i class="fa-brands fa-github"></i>
        </a>
      </div>
    <div class="container">
      <span>Copyright © 2022 Abu-Bakr Khan | All Rights Reserved </span>
    </div>
  
  
  </footer>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style>
/* footer */

a {
  color: aliceblue;
}

.links {
    font-size: 25px;
    display: flex;
    align-content: center;
    justify-content: center;
    padding-bottom: 5px;
}

i:hover {
  color: #198740;
  transition: 0.3s;
}


.footer-area .container {
  display: flex;
  justify-content: center;
  padding-bottom: 20px;
}
.footer-area {
  padding-top: 20px;
  padding-bottom: 20px;
}

i.fa-brands.fa-linkedin {
    padding-right: 10px;
}
/* footer done */
</style>
