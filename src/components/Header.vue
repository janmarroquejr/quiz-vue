<template>
  <div class="d-flex justify-content-center">
    <b-nav tabs>
      <b-nav-item disabled><strong>Quiz App</strong></b-nav-item>
      <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"],
};
</script>
