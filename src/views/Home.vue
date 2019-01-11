<template>
  <div class="home">
    <img alt="logo" class="mb-4 img-thumbnail" src="../assets/quiz.png">
    <quizs />
  </div>
</template>

<script>
// @ is an alias to /src
import Quizs from '@/components/Quizs.vue'

export default {
  name: 'home',
  components: {
    Quizs
  }
};
</script>
<style scoped>
img {
	width: 200px;
	height: 150px;
	border: none;
}
</style>