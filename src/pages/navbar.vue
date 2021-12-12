<template>
  <div class="navigation">
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <a class="navbar-brand mr-auto" href="#">
          <router-link to="/"
            ><img src="../assets/logo.svg" height="70px" alt=""
          /></router-link>
        </a>
        <ul class="my-2 navbar-nav">
          <li>
            <router-link to="/articles" tag="li" class="nav-item"
              >Articles</router-link
            >
          </li>
          <li>
            <router-link to="/casestudy" tag="li" class="nav-item"
              >Case Studies</router-link
            >
          </li>

          <li>
            <router-link to="/process" tag="li" class="nav-item"
              >My Process</router-link
            >
          </li>

          <li>
            <router-link to="/about" tag="li" class="nav-item"
              >About</router-link
            >
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<style>
.navigation {
  padding: 20px;
}
.nav-item {
  padding: 20px;
  font: Aileron;
  font-size: 20px;
  letter-spacing: 0px;
  color: #434040;
  text-transform: capitalize;
  opacity: 1;
}
nav li:hover,
nav li.router-link-active,
nav li.router-link-exact-active {
  text-decoration: underline #d82466;
  font-weight: bold;
}
</style>
