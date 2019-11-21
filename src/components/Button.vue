<template>
  <div id="buttons">
    <b-button class="buttonA" size="lg" disabled>{{ tbd }}</b-button>
    <b-button
      class="buttonB"
      size="lg"
      variant="dark"
      href="https://diabloimmortal.com/en-us/"
      >{{ learn }}</b-button
    >
  </div>
</template>

<script>
export default {
  name: "Button",
  data() {
    return {
      tbd: "Coming Soon",
      learn: "Learn More"
    };
  }
};
</script>
<style scoped>
.buttonA {
  margin-left: 40px;
  margin-right: 50px;
}
.buttonB {
  margin-left: 40px;
  margin-right: 50px;
}
</style>
