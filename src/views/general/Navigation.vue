<template>
  <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
    <div class="container">
      <a class="navbar-brand" href="#">Start Bootstrap</a>
      <button
        class="navbar-toggler navbar-toggler-right"
        type="button"
        data-toggle="collapse"
        data-target="#navbarResponsive"
        aria-controls="navbarResponsive"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        Menu
        <i class="fas fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <router-link :to="{ name: 'my-home' }" class="nav-link"
              >Home</router-link
            >
            <!--            <a  href="#" @click="$emit('set-page', 'home')">Home</a>-->
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'about' }" class="nav-link"
              >About</router-link
            >
            <!--            <a class="nav-link" href="#" @click="$emit('set-page', 'about')">About</a>-->
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'post' }" class="nav-link"
              >Sample Post</router-link
            >
            <!--            <a class="nav-link" href="#" @click="$emit('set-page', 'post')">Sample Post</a>-->
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'contact' }" class="nav-link"
              >Contact</router-link
            >
            <!--            <a class="nav-link" href="#" @click="$emit('set-page', 'contact')">Contact</a>-->
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped></style>

<script>
export default {};
</script>
