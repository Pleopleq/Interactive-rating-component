<template>
  <main class="main__container">
    <survey></survey>
  </main>
</template>

<script>
import Survey from "./components/Survey.vue";
export default {
  name: "App",
  components: { Survey },
};
</script>

<style>
@import "./assets/styles/styles.css";

.main__container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
