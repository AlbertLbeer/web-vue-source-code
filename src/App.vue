<script lang="ts">
// import TestButton from "./views/Element/TestButton.vue";
// import UserView from "./views/Element/UserView.vue";
// import QuestionView from "./views/Element/QuestionView.vue";

export default {
  name: "App",
  components: {
    // TestButton,
    // UserView,
    // QuestionView,
  },
};
</script>

<template>
  <div id="app">
    <!-- <h1 id="htitle" style="color: red">hello vue</h1> -->
    <!-- <test-button></test-button> -->
    <!-- <user-view></user-view> -->
    <!-- <question-view></question-view> -->
    <router-view></router-view>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
