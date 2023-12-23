<template>
  <VueHeader />
  <div class="board-container">
    <InfoBoard />
  </div>
</template>

<script>
import InfoBoard from './components/InfoBoard.vue'
import VueHeader from './components/VueHeader.vue'

export default {
  name: 'App',
  components: {
    InfoBoard,
    VueHeader
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  background-image: url('./assets/layered-waves-haikei.svg');
  background-size: cover;
  display: flex;
  height: 100vh;
  flex-wrap: wrap;
}

.board-container {
  align-items: center;
  display: flex;
  height: 92vh;
  width: 100vw;
  justify-content: center;
}
</style>
