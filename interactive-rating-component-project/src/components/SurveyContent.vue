<template>
  <div class="surveyContent__container">
    <div class="surveyContent__title">
      <slot name="title"></slot>
    </div>
    <div class="surveyContent__body">
      <slot name="body"></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: "SurveyContent",
};
</script>

<style></style>
