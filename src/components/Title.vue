<template>
  <div id="app">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "Title",
  data() {
    return {
      title: "Diablo Immortal"
    };
  }
};
</script>

<style>
h1 {
  color: rgb(105, 82, 40);
  padding-top: 40px;
  font-family: "Eater";
}
</style>
