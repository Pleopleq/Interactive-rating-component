<template>
  <section class="survey__container">
    <survey-content>
      <template v-slot:title>
        <div>
          <div class="starIcon">
            <img src="../assets/images/icon-star.svg" alt="" srcset="" />
          </div>
          <h1>How did we do?</h1>
        </div>
      </template>
      <template v-slot:body>
        <p>
          Please let us know how we did with your support request. All feedback
          is appreciated to help us improve our offering!
        </p>
      </template>
    </survey-content>
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
