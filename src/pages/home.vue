<template>
  <div>
    <!-- navbar  -->
    <br />
    <br />
    <!-- about demola  -->
    <div class="row about">
      <div class="col-md-6">
        <h1
          class="occupation writer"
          data-toggle="animation"
          data-animation-reset="true"
          data-animation="tada"
        >
          Writer.
        </h1>
        <h1 class="occupation drummer">Drummer.</h1>
        <h1 class="occupation ux-designer">Ux Designer.</h1>
      </div>

      <div class="col-md-6 video-container">
        <a>
          <img
            src="../assets/odetayo-ademola.png"
            height="370px"
            width="370px"
            alt=""
            class="profile-picture"
          />
        </a>
        <div class="video-case">
          <video
            autoplay
            loop
            muted
            class="background-video"
            src="../assets/background-video.mp4"
            type="video/mp4"
            height="400px"
            width="450px"
          ></video>
        </div>
      </div>
    </div>
    <br />
    <!-- projects  -->
    <div class="projects">
      <h1 class="project-highlight">Project Highlights</h1>
      <br />
      <br />
      <div class="row">
        <div class="col-md-8 mobile-fets">
          <router-link to="/fetsmobile">
            <img src="../assets/fets-mobile.png" alt="" class="fets-mobile"
          /></router-link>

          <br />
          <br />
          <br />
          <h3 class="fets"><b>Fets Mobile</b></h3>
          <p class="fets-title">Mobile, Case Study</p>
          <div class="fettss">
            <p class="about-fets">
              Fets mobile application is designed to help solve problem of the
              Day to Day Agency banking operations and transactions like
              withdrawal and airtime purchase, and payment of utility bills, all
              on the go.
            </p>
          </div>
        </div>

        <div class="col-md-4">
          <a>
            <img src="../assets/tms.png" alt="" class="tms" />
          </a>
          <br />
          <br />
          <br />
          <h3 class="fets"><b>Terminal Management Dashboard</b></h3>
          <p class="fets-title">Website, Case Study</p>
          <p class="about-fets">
            A Project Used To Monitor Transactions, Create Settlements And User
            Managements
          </p>
        </div>
      </div>
      <br />
      <br />
      <div class="row">
        <div class="col-md-8">
          <div class="hover-zoom">
            <router-link to="/powerdeal">
              <img
                src="../assets/powerdeal.png"
                alt=""
                class="fets-mobile"
                width="776px"
                height="400px"
            /></router-link>
          </div>
          <br />
          <br />
          <br />
          <h3 class="fets"><b>Powerdeals</b></h3>
          <p class="fets-title">Web Application, Case Study</p>
          <div class="fettss">
            <p class="about-fets">
              Power Deal Is An Electricity Bill Payment Service That Enables You
              Recharge And Buy Power Conveniently.
            </p>
          </div>
        </div>

        <div class="col-md-4">
          <a>
            <img
              src="../assets/megalek.png"
              alt=""
              class="tms"
              width="398px"
              height="400px"
            />
          </a>
          <br />
          <br />
          <br />
          <h3 class="fets"><b>MEGALEK HOSPITAL TMS</b></h3>
          <p class="fets-title">Web Application, Prototype</p>
          <!-- <p class="about-fets">
            A Project Used To Monitor Transactions, Create Settlements And User
            Managements
          </p> -->
        </div>
      </div>
      <br />
      <div>
        <div class="row">
          <div class="col-md-9">
            <div class="another-heading">
              <h1 class="interests">Some Interesting Projects</h1>

              <img
                src="../assets/Line 3.svg"
                width="500px"
                alt=""
                class="red-line"
              />
            </div>
          </div>
        </div>
      </div>
      <br />
      <br />
      <br />

      <div>
        <div class="row">
          <div class="col-md-4">
            <p class="fets"><b>Stanbic Bank</b></p>
            <p class="about-project">
              A web and mobile banking application designed to facilitate Agency
              banking operations and transactions. e.g, cash-out, airtime
              purchases and other bills payment
            </p>
          </div>
          <div class="col-md-4">
            <p class="fets"><b>Remote Upgrade</b></p>
            <p class="about-project">
              This web application allows super agents automatically push update
              to POS terminal
            </p>
          </div>
          <div class="col-md-4">
            <p class="fets"><b>Megalek Hospital Management Dashboard</b></p>
            <p class="about-project">
              A Project Used To Monitor Transactions, Create Settlements And
              User Managements
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.about {
  padding-left: 60px;
}
.occupation {
  font-weight: 1000;
  font-size: 4rem;
  font-family: "Montserrat", sans-serif;
  letter-spacing: 3px;
  color: #333333;
  opacity: 1;
  width: min(700px, 80%);
}
.occupation:hover {
  animation: 1s slide-right;
  animation-delay: 0.5s;
}

@keyframes slide-right {
  from {
    margin-left: 150px;
  }

  to {
    margin-left: 0%;
  }
}
.profile-picture {
  float: right;
  margin-right: -250px;
  margin-top: -30px;
}
.background-video {
  float: right;
  margin-right: -250px;
  margin-top: -30px;
}
.video-container {
  position: relative;
  width: 5%;
  height: 5%;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}
.video-container a {
  text-align: center;
  z-index: 1;
}
.video-case {
  /* position: absolute; */
  top: 0;
  left: 0;
  width: 5%;
  height: 5%;
}
.projects {
  padding-left: 60px;
}
.project-highlight {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 4.5rem;
  font-weight: 800;
  letter-spacing: 3.04px;
  color: #e3e3e3;
  opacity: 1;
}
.fets {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  letter-spacing: 0.77px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
}
.fets-mobile {
  transition: width 1s, height 1s;
  width: 70%;
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

.fets-title {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 16px;
  letter-spacing: 0.58px;
  color: #767676;
  text-transform: capitalize;
  opacity: 1;
  width: min(500px, 80%);
}
.fettss {
  width: min(500px, 80%);
}
.about-fets {
  text-align: left;
  font-family: "Poppins", sans-serif;
  font-size: 18px;
  letter-spacing: 0.58px;
  color: #767676;
  text-transform: capitalize;
  opacity: 1;
  width: min(500px, 80%);
}
.tms {
  padding-right: 70px;
  width: 100%;
}
@media all and (max-width: 480px) {
  .fets-mobile {
    width: 100%;
  }
}
.interests {
  width: 622px;
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 4.5rem;
  font-weight: 700;
  letter-spacing: 2.04px;
  color: #d6d6d6;
  opacity: 1;
  width: min(500px, 80%);
}
.about-project {
  text-align: left;
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  letter-spacing: 0.7px;
  color: #767676;
  text-transform: capitalize;
  opacity: 1;
}
.another-heading {
  display: flex;
}
.red-line {
  margin-top: 200px;
}
</style>
