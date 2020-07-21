<template>
  <div id="app">
    <navigation></navigation>
    <router-view></router-view>
  </div>
</template>

<script>
import Navigation from "./views/general/Navigation";

export default {
  components: {
    Navigation
  }
};
</script>
