<template>
  <!-- <div class="video">
    <section>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/RtSmAwpVHsA"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </section>

  </div>-->
  <div>
    <b-jumbotron id="jumbo">
      <iframe
        width="600"
        height="350"
        src="https://www.youtube.com/embed/RtSmAwpVHsA"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </b-jumbotron>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* .backgroundI {
  height: 100%;
  width: 100%;
  position: absolute;
} */

#jumbo {
  position: relative;
  background: none;
  height: 400px;
}

#buttonO {
  position: relative;
}
</style>
