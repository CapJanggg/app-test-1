<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="./assets/logo.svg" alt="" width="30" height="24" />
        </a>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link"> <RouterLink to="/">Menu 1</RouterLink> </a>
            </li>
            <li class="nav-item">
              <a class="nav-link"> <RouterLink to="Contact">Menu 2</RouterLink> </a>
            </li>
            <li class="nav-item">
              <a class="nav-link"> <RouterLink to="/AboutView">Menu 3</RouterLink> </a>
            </li>
            <RouterView />
            <!-- nav>
              <li><RouterLink to="/">Home</RouterLink></li>
              <li><RouterLink to="/about">About</RouterLink></li>
              <li><RouterLink to="/contact">Contact</RouterLink></li>
            </nav> -->
          </ul>
        </div>
      </div>
    </nav>
    <div class="container mt-3">
      <div class="row">
        <div class="divbox-1"></div>
        <div class="divbox-2"></div>
        <div class="divbox-3"></div>
      </div>

      <div class="row">
        <div class="divbox-4"></div>
        <div class="divbox-5"></div>
      </div>

      <div class="row">
        <div class="divbox-6"></div>
      </div>

    </div>
  </header>
</template>

<script>
import { RouterLink, RouterView } from "vue-router";

export default {};
</script>

<style>
.divbox-1 {
  width: 300px;
  height: 70px;
  padding: 60px;
  border: 1px solid red;
}

.divbox-2 {
  width: 300px;
  height: 70px;
  padding: 60px;
  border: 1px solid red;
}

.divbox-3 {
  width: 300px;
  height: 70px;
  padding: 60px;
  border: 1px solid red;
}

.divbox-4 {
  width: 300px;
  height: 70px;
  padding: 60px;
  border: 1px solid red;
}

.divbox-5 {
  width: 300px;
  height: 70px;
  padding: 60px;
  border: 1px solid red;
}

.divbox-6 {
  width: 300px;
  height: 70px;
  padding: 60px;
  border: 1px solid red;
}
</style>
