<template>
  <footer>
    <hr />
    <br />
    <div class="row">
      <div class="col-md-3">
        <p class="rights">All rights Reserved</p>
      </div>
      <div class="col-md-6 coders">
        <p class="rights">Designed by <b>Ademola Odetayo</b></p>
        <br />
        <p class="rights">Developed by <b>Eguzoro Chimamaka</b></p>
      </div>
      <div class="col-md-3 socials">
        <a href="">
          <img src="../assets/instagram.png" alt="" />
        </a>
        <a href="">
          <img src="../assets/linkedin.png" alt="" />
        </a>
        <a href="">
          <img src="../assets/twitter.png" alt="" />
        </a>
      </div>
    </div>
  </footer>
</template>

<style>
footer {
  padding: 30px;
}
.coders {
  display: inline-flex;
  justify-content: space-evenly;
}
.rights {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 15px;
  letter-spacing: 0.51px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
}
.socials {
  display: flex;
  justify-content: space-evenly;
}
</style>
