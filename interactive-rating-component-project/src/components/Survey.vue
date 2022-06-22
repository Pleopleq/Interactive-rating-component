<template>
  <section class="survey__container">
    <survey-content></survey-content>
  </section>
</template>

<script>
import SurveyContent from "./SurveyContent.vue";
export default {
  name: "Survey",
  components: { SurveyContent },
};
</script>

<style>
.survey__container {
  height: 300px;
  width: 300px;
  background-color: var(--dark-blue);
  border-radius: 12px;
}
</style>
