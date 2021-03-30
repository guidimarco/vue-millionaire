<template>
    <div class="container">
        <Question />
        <Answer />
    </div>
</template>

<script>
import Question from "@/components/Question.vue";
import Answer from "@/components/Answer.vue";

export default {
  name: "Container",
  components: {
      Question,
      Answer
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
