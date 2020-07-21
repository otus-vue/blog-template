<template>
  <div id="app">
    <Navigation></Navigation>
    <Home></Home>
  </div>
</template>

<script>
import Navigation from "./views/general/Navigation";
import Home from "./views/Home";

export default {
  components: {
    Navigation,
    Home
  }
};
</script>
