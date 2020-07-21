<template>
  <div>
    <!-- Page Header -->
    <slot name="header"></slot>

    <!-- Main Content -->
    <slot name="main"></slot>

    <hr />

    <!-- Footer -->
    <Footer></Footer>
  </div>
</template>

<style lang="scss" scoped></style>

<script>
import Footer from "./Footer";

export default {
  components: {
    Footer
  }
};
</script>
