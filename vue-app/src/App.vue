<template>
  <div id="app">
    <Portifolio />
  </div>
</template>

<script>
import Portifolio from './components/Portifolio.vue'

export default {
  name: 'App',
  components: {
    Portifolio,
  }
}
</script>

<style lang="scss">
@import '~bulma';

body {
  background-color: #FEAEA7;
  color: #ffffff;
  overflow: hidden;
}

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&family=Titan+One&display=swap');

.container {
  padding-bottom: 0.75em;
}
//alt shift A
#welcome-text {
  font-family: 'Titan One', cursive;
  font-style: normal;
  font-weight: normal;
  font-size: 60px;
  line-height: 69px;
  color:#ffffff;
}

.hello-container {
  position: relative;
}

.hello-title {
  position: relative;
  z-index: 2;
}

#circle-image {
  position: absolute;
  height: 150px;
  width: 115px;
  left: calc(50% - 175px);
  top: calc(75% - 135px);
}

.title {
  font-family: 'Titan One', cursive;
  font-style: normal;
  font-weight: normal;
  font-size: 30px;
  line-height: 34px;
  color: #ffffff;
  padding: 0 0 0.30em 0;
  margin: 0 0 0 0 !important;
  z-index: 1;
}

.subtitle {
  color: #ffffff;
  font-family: 'Roboto', sans-serif;
  padding: 0 0.10em 0.60em 0.10em;
  margin: 0 0 0 0 !important;
}

a {
  color: #ffffff;
}

.icon-image {
  margin: 0.4em 1.2em 0 1.0em;
  padding: 0.60em 0 0.60em 0;
}

#social-medias {
  font-family: 'Roboto', sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 25px;
  line-height: 23px;
  padding: 0.60em 0 0.60em 0;
}

.footer {
  padding: 0.60em 0 0.60em 0;
  background-color: #FEAEA7;
}
</style>
