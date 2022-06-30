<template>
  <section class="surveyContent__container">
    <div class="surveyContent__title">
      <slot name="title"></slot>
    </div>
    <div class="surveyContent__body">
      <slot name="body"></slot>
    </div>
    <div class="surveyContent__rating">
      <form>
        <button>1</button>
        <button>2</button>
        <button>3</button>
        <button>4</button>
        <button>5</button>
        <button>Submit</button>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: "SurveyContent",
};
</script>

<style>
.surveyContent__container {
  height: 100%;
}

.surveyContent__title > * {
  font-size: 1.2em;
  margin-bottom: 14px;
}

.surveyContent__body > * {
  font-size: 12px;
  opacity: 0.8;
  line-height: 1.1rem;
}
</style>
