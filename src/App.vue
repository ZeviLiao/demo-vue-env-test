<template>
  <div id="app">
    <HelloWorld :msg="msg"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

import conf from "./config";

export default {
  name: "app",
  components: {
    HelloWorld
  },
  data() {
    return {
      msg: conf.userCenterDomain
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
