<template>
  <div id="app">
    <HelloWorld msg="Hello World" />
    <Gasket msg="シェルピンスキーのギャスケット" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Gasket from "./components/Gasket.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Gasket
  }
};
</script>