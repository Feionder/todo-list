<script setup>
import TodoList from './components/TodoList.vue' 
</script>

<template>

  <header>

    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="container">
      <HelloWorld msg="You did it!" />
      <todo-list></todo-list>
    </div>
    
  </header>

  <main>

    <TheWelcome />

  </main>

</template>

<style scoped>

*{
  box-sizing: border-box;
}

.container {
  max-width: 600px;
  margin: 0 auto;
}

#app {
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center */
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}

.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}
</style>
