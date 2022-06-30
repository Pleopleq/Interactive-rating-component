<template>
  <section class="survey__container">
    <survey-content>
      <template v-slot:title>
        <div>
          <div class="starIcon">
            <img src="../assets/images/icon-star.svg" alt="star icon" />
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
  display: flex;
  align-items: center;
  background-color: var(--dark-blue);
  border-radius: 12px;
  padding: 1.6rem 1.6rem 1.2rem 1.6rem;
}

.starIcon {
  background-color: var(--medium-grey);
  display: flex;
  justify-content: center;
  align-items: center;
  width: 33px;
  height: 33px;
  border-radius: 6rem;
  margin-bottom: 1rem;
}

.starIcon > img {
  height: 15px;
}
</style>
