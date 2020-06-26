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
.welcome-text {
  font-family: 'Titan One', cursive;
  font-style: normal;
  font-weight: normal;
  font-size: 60px;
  line-height: 69px;
  color:#ffffff;
  display: inline-block;
}

.animated-text {
  color:#FF9800;
  display: inline-block;
}

.top-screen {
  margin-bottom: 150px;
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
  animation:spin 6s linear infinite;
  -webkit-animation:spin 6s linear infinite;
  -moz-animation:spin 6s linear infinite;
}

@-moz-keyframes spin { 
  100% { 
    -moz-transform: rotate(360deg); 
  }
}
@-webkit-keyframes spin { 
  100% { 
    -webkit-transform: rotate(360deg);
  } 
}
@keyframes spin {
  100% {
    -webkit-transform: rotate(360deg);
    transform:rotate(360deg);
  }
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

//Source: https://codepen.io/geoffgraham/pen/bxEVEN
:root {
  --mainColor: #FF9800;
}

span {
  background: linear-gradient(to bottom, var(--mainColor) 0%, var(--mainColor) 100%);
	background-position: 0 100%;
	background-repeat: repeat-x;
	background-size: 2.5px 2.5px;
  color: #ffffff;
  text-decoration: none;
}

span:hover {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg id='squiggle-link' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' xmlns:ev='http://www.w3.org/2001/xml-events' viewBox='0 0 20 4'%3E%3Cstyle type='text/css'%3E.squiggle{animation:shift .3s linear infinite;}@keyframes shift {from {transform:translateX(0);}to {transform:translateX(-20px);}}%3C/style%3E%3Cpath fill='none' stroke='%23ff9800' stroke-width='2' class='squiggle' d='M0,3.5 c 5,0,5,-3,10,-3 s 5,3,10,3 c 5,0,5,-3,10,-3 s 5,3,10,3'/%3E%3C/svg%3E");
  background-position: 0 100%;
  background-size: auto 4px;
  background-repeat: repeat-x;
  text-decoration: none;
}
</style>
