<template>
  <div class="about">
    <h1>Alt Todos</h1>
    <div class="about_text">
      <p>Todo apps are designed to help you keep track of your daily tasks and activities. They can help you stay on top of your schedule and make sure you don't miss any important deadlines.</p>
      <p>This app was built using Vue 3, Vue Router, Sass, iconify, and uid.</p>    
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  h1 {
    margin-top: 20px;
    margin-bottom: 20px;
    text-align: center;
  }
  .about_text {
    margin: 0 auto;
    width: 50%;
    text-align: center;
  }

}
</style>
