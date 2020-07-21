<template>
  <div>
    <h1>User</h1>
    <router-view></router-view>
  </div>
</template>

<style lang="scss" scoped></style>

<script>
export default {
  props: ["userId"],
  mounted() {
    alert("User");
  }
};
</script>
