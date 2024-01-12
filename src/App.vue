<template>
  <div id="app">
    <HeaderComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/header_component.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
  },
};
</script>

<style lang="scss">
:root {
  --primary-color: #007DFA;
  --primary-weak: #E0EFFE;
  --white: #FFFFFF;
  --boder: #DDDEDF;
  --text-primary: #101012;
  --text-secondary: #5A5A5D;

  --title-large: 40px;
  --title-regular: 32px;
  --text-large: 24px;
  --text-regular: 16px;
}
html,
body,
ul {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  box-sizing: border-box;
}

#app {
  font-family: Roboto, sans-serif;
}
</style>
