<template>
  <header
    class="masthead"
    :style="'background-image: url(\'' + bgImage + '\')'"
  >
    <div class="overlay"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-10 mx-auto">
          <div class="site-heading">
            <h1><slot name="header"></slot></h1>
            <span class="subheading"><slot name="subheader"></slot></span>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped></style>

<script>
export default {
  props: ["bgImage"]
};
</script>
