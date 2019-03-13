<template>
  <div id="app">
    <h1>Welcome to Tic Tac Toe</h1>
    <!-- The main interface only has one component: the tic tac toe board. -->
    <TicTacToe id="game-board"/>
  </div>
</template>

<script>
import TicTacToe from './components/TicTacToe.vue'
export default {
  name: 'app',
  components: {
    TicTacToe
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#game-board{
  margin: 2rem auto;
  width: 50%;
  padding: 10px;
}
</style>
