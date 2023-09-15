<template>
  <div class="about">
    <h1>{{ aboutPage.title }}</h1>
    <p>{{ aboutPage.content1 }}</p>
    <p>{{ aboutPage.content2 }}</p>
    <p>{{ aboutPage.content3 }}</p>
  </div>
</template>

<script setup>
const aboutPage = {
  title: 'This is an about page',
  content1:
    'Vue Todos is a CRUD Todo tracking application created for a Vue 3 Crash Course by Burnett Miao',
  content2:
    "Track your daily task's using this todo tracker with abilities to save, complete, edit & delete todos.",
  content3:
    'Feel free to add no to this application with functionalities such as the ability to drag and reorder todos, animate creation/deletion of todos or even create this into a full stack application with the ability to have different lists for different days of tracking todos!',
};
</script>

<style lang="scss" scoped>
.about {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  width: 100%;
  margin: 0 auto;
  padding: 40px 16px;

  p {
    font-weight: 100;
    margin-top: 1rem;
  }
}
</style>
