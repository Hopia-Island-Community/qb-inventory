<template>
  <b-container id="main" fluid style="padding: 0;">
    <router-view />
  </b-container>
</template>

<style lang="scss">

  #main {
    background-color: rgb(81, 81, 81);
    height: 100%;
    width: 100%;
  }

  body {
    margin: 0;
    padding: 0;
    height: 100vh;
    width: 100vw;
    opacity: 0.95;
    background-image: url('/public/background.jpg');
    overflow-x: hidden;
  }

  * {
    box-sizing: border-box;
  }
</style>
