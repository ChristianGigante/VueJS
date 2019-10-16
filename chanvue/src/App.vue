<template>
  <div>
    <div id="app">
      <p>{{ msg }}</p>
    </div>
    <App2 />
    <App3 />
    <App4 />
  </div>
</template>


<script>
import App2 from "../src/exercises/App2";
import App3 from "../src/exercises/App3";
import App4 from "../src/exercises/App4";



export default {
  data() {
    return {
      msg: "Christian Gwapo"
    };
  },
  components: {
      App2,
      App3,
      App4
  }
  
};
</script>

<style >
#app {
    color:red;
}
#app-2 {
    color:blue
}
#app-3 {
    color:green;
}
</style>