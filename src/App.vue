<template>
  <div id="app">
    <Header />
    <img alt="backG" class="backgroundI" src="./assets/dibg.png" />

    <b-container class="bv-example-row">
      <b-row class="text-center" id="name-title">
        <b-col><Title /></b-col>
      </b-row>
      <b-row class="text-center" id="mainV">
        <b-col><Video /></b-col>
        <b-col><External /></b-col>
      </b-row>
      <b-row class="text-center">
        <b-col></b-col>
        <b-col cols="8"> <Button /></b-col>
        <b-col></b-col>
      </b-row>
      <b-row class="text-center">
        <b-col><Email /></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Video from "./components/Video.vue";
import Button from "./components/Button.vue";
import Title from "./components/Title.vue";
import Email from "./components/Email.vue";
import External from "./components/External.vue";

export default {
  name: "app",
  components: {
    Header,
    Video,
    Button,
    Title,
    Email,
    External
  },
  data() {
    return {
      message: {
        info: "I wish to recieve info and news."
      }
    };
  }
};
</script>

<style>
.backgroundI {
  height: 100%;
  width: 100%;
  position: absolute;
}
#mainV {
  height: 400px;
}
</style>
