<template>
  <footer>
    <hr />
    <br />
    <div class="row">
      <div class="col-md-3">
        <p class="rights">All rights Reserved</p>
      </div>
      <div class="col-md-3 coders">
        <p class="rights">Designed by <b>Ademola Odetayo</b></p>
        <br />
      </div>
      <div class="col-md-3 coders">
        <p class="rights">Developed by <b>Eguzoro Chimamaka</b></p>
      </div>
      <div class="col-md-3 socials">
        <a href="https://instagram.com/funmetor?utm_medium=copy_link">
          <img src="../assets/instagram.png" alt="" />
        </a>
        <a href="http://linkedin.com/in/odetayo-ademola">
          <img src="../assets/linkedin.png" alt="" />
        </a>
        <a href="https://twitter.com/demochlala?s21">
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
/* .coders {
  display: inline-flex;
  justify-content: space-evenly;
} */
.rights {
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
