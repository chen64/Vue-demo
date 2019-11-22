<template>
  <div id="info">
    <h2>{{ header }}</h2>
    <b-button
      class="buttonY"
      size="lg"
      href="https://www.youtube.com/user/diablo"
      variant="danger"
      >{{ youtube }}</b-button
    >
    <b-button
      class="buttonY"
      size="lg"
      href="https://twitter.com/Diablo"
      variant="primary"
      >{{ twitter }}</b-button
    >
  </div>
</template>
<script>
export default {
  name: "External",
  data() {
    return {
      youtube: "Youtube",
      twitter: "Twitter",
      header: "Check these out for more Diablo news"
    };
  }
};
</script>
<style scoped>
#info {
  margin-top: 30%;
  background-image: url("../assets/paper.jpg");
  background-size: cover;
}
.buttonY {
  margin: 30px;
}
</style>
