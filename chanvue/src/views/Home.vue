<template>
  <div>
    <Navbar />
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Test />
  </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Test from "./Test";
import Navbar from "../components/Navbar";

export default {
  name: "home",
  components: {
    // HelloWorld
    Test,
    Navbar
  }
};
</script>
