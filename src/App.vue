<template>
  <Home></Home>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Home from "./components/Home";
export default {
  name: "App",
  components: {
    HelloWorld,
    Home
  }
};
</script>

<style lang="scss">
html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
}
::-webkit-input-placeholder {
  color: #ccc;
  font-style: italic;
  opacity: 1;
}
::placeholder {
  /* Chrome, Firefox, Opera, Safari 10.1+ */
  color: #ccc;
  font-style: italic;
  opacity: 1; /* Firefox */
}
:-ms-input-placeholder {
  /* Internet Explorer 10-11 */
  color: #ccc;
  font-style: italic;
}
::-ms-input-placeholder {
  /* Microsoft Edge */
  color: #ccc;
  font-style: italic;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  word-break: break-all;
  word-wrap: break-word;
  text-align: center;
  color: #2c3e50;
}
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: block;
  margin: 0 10px;
  text-align: left;
}
a {
  color: #42b983;
}
</style>
