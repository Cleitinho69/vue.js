<template>
  <div id="telaPrincipal">
    <escrever/>
  </div>
</template>

<script>

import escrever from './components/escrever.vue';

export default {
  name: 'App',
  components: {
    escrever
  }
}
</script>

<style>
  .center{
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .column{
    flex-direction: column;
  }

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body{
    width: 100vw;
    height: 100vh;

    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

<style scoped>

#telaPrincipal{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;

  width: 300px;
  height: 300px;

  background-color: #f0f0f0;

  box-shadow: 2px 0 10px 5px rgba(0,0,0,0.1);
}
</style>
