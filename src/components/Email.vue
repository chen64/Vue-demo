<template>
  <div id="emailPlace">
    <input type="text" v-model="message.email" placeholder="Email" />
    <b-form-checkbox
      id="checkbox"
      v-model="message.info"
      name="checkbox"
      value="I want to recieve news and info."
      unchecked-value="I want to recieve news and info."
      >{{ message.info }}
    </b-form-checkbox>
    <b-button variant="success" id="button">Submit</b-button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: {
        email: "",
        info: "I want to recieve news and info."
      }
    };
  }
};
</script>

<style scoped>
#emailPlace {
  padding-top: 20px;
}
#checkbox {
  margin-left: 50px;
}
</style>
