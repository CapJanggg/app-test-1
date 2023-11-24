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
        <div class="divbox-1">1 is a flys.</div>
        <div class="divbox-2">2 is a fish.</div>
      </div>

      <div class="divbox-5">5 is a launghing.</div>

      <div class="row">
        <div class="divbox-3">3 is not a tree.</div>
        <div class="divbox-4">4 will win three of a kind.</div>
      </div>

        <div class="divbox-6">prepare your mop.</div>

    </div>
    
  </header>
</template>

<script>
import { RouterLink, RouterView } from "vue-router";

export default {};
</script>

<style>
.container {
  width: auto;
  display: flex;
  flex-direction: column;
}

.divbox-1 {
  width: 300px;
  height: 10px;
  color: rgb(232, 241, 241);
  background: rgba(88, 28, 20, 0.705);
  margin: 10px 0;
  padding: 50px;
  border: 1px solid red;
}

.divbox-2 {
  width: 300px;
  height: 70px;
  margin: 10px 0;
  padding: 60px;
  color: rgb(232, 241, 241);
  background: rgba(18, 112, 60, 0.705);
  border: 1px solid red;
}

.divbox-3 {
  width: 300px;
  height: 70px;
  margin: 10px 0;
  padding: 60px;
  color: rgb(232, 241, 241);
  background: rgba(49, 20, 88, 0.733);
  border: 1px solid red;
}

.divbox-4 {
  width: 300px;
  height: 70px;
  margin: 10px 0;
  padding: 60px;
  color: rgb(232, 241, 241);
  background: rgba(20, 66, 88, 0.829);
  border: 1px solid red;
}

.divbox-5 {
  width: 300px;
  height: 70px;
  margin: 10px 0;
  padding: 60px;
  color: rgb(232, 241, 241);
  background: rgba(146, 16, 185, 0.699);
  border: 1px solid red;
}

.divbox-6 {
  width: 300px;
  height: 70px;
  margin: 10px 0;
  padding: 60px;
  color: rgb(232, 241, 241);
  background: rgba(83, 88, 20, 0.753);
  border: 1px solid red;
}
</style>
