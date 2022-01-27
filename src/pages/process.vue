<template>
  <div class="content">
    <br />
    <br />
    <div class="process-heading">
      <h1 class="process">My Process</h1>
      <video
        autoplay
        loop
        muted
        class="rocket-video"
        src="../assets/rocket-in-space.mp4"
        type="video/mp4"
        height="200px"
      ></video>
    </div>
    <div class="wordings">
      <p>
        My Process is quite simple but my approach changes based on the nature
        and scope of the projects, but it mostly revolves around this:
      </p>
    </div>
    <br />
    <br />
    <br />

    <img src="../assets/design-process.png" alt="" class="design-process" />

    <br />
    <br />
    <br />
    <div class="row">
      <div class="col-md-3 info">
        <div><img src="../assets/dotted-arrow.svg" alt="" class="line" /></div>
        <div>
          <h4 class="first-head">Research + Discover</h4>
          <div class="long-list">
            <p>Contextual Inquiry</p>
            <p>User + Market Research</p>
            <p>Competitive Analysis</p>
            <p>Observation</p>
            <p>Hypothesis Validation</p>
          </div>
        </div>
      </div>
      <div class="col-md-3 info">
        <div>
          <img src="../assets/dotted-arrow.svg" alt="" class="line-2" />
        </div>
        <div>
          <h4 class="first-head">Ideation + Define</h4>
          <div class="long-list">
            <p>Card Sorting + Tree Texting</p>
            <p>User Flows</p>
            <p>Experience Mapping</p>
          </div>
        </div>
      </div>
      <div class="col-md-3 info">
        <div>
          <img src="../assets/dotted-arrow.svg" alt="" class="line-3" />
        </div>
        <div>
          <h4 class="first-head">Design + Testing</h4>
          <div class="long-list">
            <p>A/B Testing</p>
            <p>Userablity Testing</p>
            <p>Heuristic Evaluation</p>
            <p>Adobe XD</p>
            <p>Figma</p>
            <p>Invision</p>
          </div>
        </div>
      </div>
      <div class="col-md-3 info">
        <div>
          <img src="../assets/dotted-arrow.svg" alt="" class="line-4" />
        </div>
        <div>
          <h4 class="first-head">Deliver +Handover</h4>
          <div class="long-list">
            <p>High Fidelity Prototype</p>
            <p>Style Guilde</p>
            <p>Wireframe Annotation</p>
            <p>Design Presentation</p>
            <p>Html/Css</p>
          </div>
        </div>
      </div>
    </div>
    <br /><br /><br /><br /><br />

    <div class="row">
      <div class="col-md-6 location">
        <p class="location"><b> My Location </b></p>

        <p class="lagos">Lagos, Nigeria</p>
        <p class="lagos">Work Remotely From Wherever</p>
      </div>
      <div class="col-md-6 resume">
        <p class="location"><b> Work Inquires </b></p>

        <p class="lagos">Interested In Woking With Me?</p>
        <a
          href="https://drive.google.com/file/d/1WURwEWkDGJkR9BT7yxMWKKZAR0OjtiL7/view?usp=sharing"
        >
          <img src="../assets/resume.svg" alt="" />
        </a>
        <p class="lagos">Contact Me <b>ademolaodetayo@gmail.com</b></p>
      </div>
    </div>
  </div>
</template>
<style>
.content {
  padding-left: 60px;
  padding-right: 60px;
}
.process-heading {
  display: flex;
  flex-wrap: wrap;
}
.process {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 70px;
  font-weight: 800;
  letter-spacing: 3.2px;
  color: #333333;
  text-transform: capitalize;
  opacity: 1;
}

.rocket-video {
  margin-top: -80px;
}
@media (max-width: 40em) {
  .rocket-video {
    display: none;
  }
}
.wordings {
  text-align: left;
  font-family: "Montserrat", sans-serif;
  font-size: 1rem;
  letter-spacing: 0px;
  color: #696969;
  opacity: 1;
}
.design-process {
  width: 100%;
}
@media all and (max-width: 480px) {
  .design-process {
    width: 100%;
  }
}
.performance {
  display: flex;
  justify-content: space-evenly;
}
.description {
  width: 80px;
  text-align: center;
  font: 22px/30px Chalkboard;
  letter-spacing: 0px;
  color: #292525;
  text-transform: lowercase;
  opacity: 1;
}
.info {
  display: flex;
}
.line {
  height: 236px;
}
.line-2 {
  height: 160px;
}
.line-3 {
  height: 280px;
}
.line-4 {
  height: 236px;
}

.resume {
  float: right;
}
.location {
  font-family: "Poppins", sans-serif;
  font-size: 22px;
  font-weight: medium;
  letter-spacing: 0px;
  color: #292525;
  text-transform: capitalize;
  opacity: 1;
}
.lagos {
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  color: #00000086;
  text-transform: capitalize;
  opacity: 1;
}
.long-list {
  font-family: "Poppins", sans-serif;
  font-size: 15px;
  color: #00000086;
  text-transform: capitalize;
  opacity: 1;
}
.first-head {
  font-family: "Poppins", sans-serif;
  font-size: 20px;
  letter-spacing: 0px;
  color: #292525;
  text-transform: capitalize;
  opacity: 1;
}
</style>
