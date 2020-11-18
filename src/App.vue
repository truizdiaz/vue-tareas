<template>
  <div class="fondo">
    <Navbar />
    <Tarea />
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Tarea from "./components/Tarea";

export default {
  name: "App",
  components: {
    Navbar,
    Tarea,
  },
};
</script>

<style>
.fondo {
  background-image: url("./assets/fondo1.jpg");
  height: 100vh;
}
</style>
