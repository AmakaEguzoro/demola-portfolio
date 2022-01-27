<template>
  <div class="body">
    <div>
      <h1 class="head">Case Studies</h1>
    </div>
    <br />
    <br />

    <div class="fets-project">
      <router-link to="/fetsmobile">
        <img src="../assets/fets-mobile.png" alt="" class="fets-mobile"
      /></router-link>

      <br />
      <br />
      <div class="the-title">
        <p class="name">Fets Mobile</p>
        <p class="function">Mobile, Case Study</p>
      </div>
      <p class="explain">
        Fet Mobile Application Is Designed To Help Solve Problems Of The Day To
        Day Agency Banking Operations And Transactions Like Withdrawal And
        Airtime Purchase, And Payment Of Utility Bills All On The Go.
      </p>
    </div>

    <div class="fets-project">
      <router-link to="/powerdeal">
        <img src="../assets/powerdeal.png" alt="" class="fets-mobile"
      /></router-link>

      <br />

      <div class="the-title">
        <p class="name">Powerdeals</p>
        <p class="function">Web Application, Case Study</p>
      </div>
      <p class="explain">
      Power Deal Is An Electricity Bill Payment Service That Enables You Recharge And Buy Power Conveniently.
      </p>
    </div>

    <div class="row extra">
    
      <div class="col-md-6 terminal">
        <a href="https://xd.adobe.com/view/798caf82-00f9-4970-9d9a-0528eedd6743-2cdf/">

      
        <img src="../assets/tms.png" class="tms-image" alt="" />
        <p class="project-title">Terminal Management Dashboard</p>
        <p class="terminal-words">
       Lorem Ipsum Dolor Sit Amet, Consetetur Sadipscing Elitr, Sed Diam Nonumy Eirmod Tempor Invidunt Ut Labore Et Dolore Magna Aliquyam Erat, Sed Diam Voluptua. At Vero Eos Et Accusam Et Justo Duo Dolores Et Ea Rebum. Stet Clita Kasd Gubergren, No Sea Takimata Sanctus Est Lorem Ipsum Dolor Sit Amet. Lorem Ipsum Dolor Sit Amet, Consetetur
        </p>
          </a>
      </div>
      <div class="col-md-6 uba">
        <a href="https://xd.adobe.com/view/8f9564d4-f83e-4fbe-8ab8-ecf82240caa4-dac6/">
        <img src="../assets/megalek.png" class="megalek-image" alt="" />
        <p class="project-title">MEGALEK HOSPITAL TMS</p>
        <p class="terminal-words">Web Application, Prototype</p>
        </a>
      </div>
    
    </div>
  </div>
</template>
<style>
.body {
  padding-left: 80px;
  padding-right: 80px;
}
.head {
  width: 418px;
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 70px;
  font-weight: 800;
  letter-spacing: 3.2px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
}
.fets-mobile {
  transition: width 1s, height 1s;
  width: 100%;
}
@media all and (max-width: 480px) {
  .fets-mobile {
    width: 100%;
  }
}

.fets-mobile:hover {
  height: 430px;
  width: 776px;
}
.fets-project {
  height: 788px;
  margin: auto;
  width: 50%;
}
.the-title {
  display: flex;
  width: min(500px, 80%);
}
.name {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: 800;
  letter-spacing: 0.77px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
}
.function {
  font-family: "Montserrat", sans-serif;
  padding-left: 20px;
  padding-top: 5px;
  font-size: 15px;
  letter-spacing: 0.58px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
}
.explain {
  text-align: left;
  font-family: "Poppins", sans-serif;
  font-size: 16px;
  letter-spacing: 0.4px;
  color: #767676;
  text-transform: capitalize;
  opacity: 1;
  width: min(500px, 80%);
}
/* .terminal {
  float: right;
  position: relative;
} */
.terminal-words {
  width: 400px;
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  letter-spacing: 0.4px;
  color: #767676;
  text-transform: capitalize;
  opacity: 1;
  width: min(500px, 80%);
}
.project-title {
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: 800;
  letter-spacing: 0.77px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
  width: min(500px, 80%);
}
.tms-image {
  width: 60%;
}
@media all and (max-width: 480px) {
  .tms-image {
    width: 100%;
  }
}
.megalek-image {
  width: 60%;
}
@media all and (max-width: 480px) {
  .megalek-image {
    width: 100%;
  }
}
/* .extra {
  padding-left: 100px;
  padding-right: 100px;
} */
</style>
