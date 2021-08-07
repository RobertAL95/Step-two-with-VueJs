<template>
  <Form />
</template>

<script>
import Form from "./components/Form.vue";
export default {
  name: "App",
  components: {
    Form: Form,
  },
};
</script>

<style lang="scss" >
@import "./styles/_variables.scss";

html,
body {
  background: $bg;
  color: $color;
  margin: 0;
  font-family: sans-serif;
}

h2 {
  margin-top: 0;
  height: 50px;
  background: $colorh2;
  font-style: italic;
  text-align: center;
  //border-bottom: 1px solid $color-border;
  paddin-bottom: 10px;
}
</style>
