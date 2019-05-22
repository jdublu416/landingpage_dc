<template>
  <div id="app">
    <Video/>
    <Header/>
    <div class="title-container">
      <h2 id="main-title">We are Data Concepts</h2><br/>
      <h1 id="main-subtitle">Driving Digital Transformations</h1>
    </div>
  </div>
</template>
 
<script>
import Header from "./components/layouts/Header";
import Video from "./components/layouts/Video";

export default {
  name: "app",
  components: {
    Header,
    Video
  }
};
</script>

<style>

@keyframes textEffectTest{
  0%   {font-size: 2.5rem;}
  25%  {font-size: 2.55rem;}
  50%  {font-size: 2.55rem;}
  100% {font-size: 2.5rem;}
}
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
 
}

body{
  background: radial-gradient(closest-corner, rgba(255, 255, 255, 0.0),rgba(255, 255, 255, 0.25), rgba(10, 10, 10, .25), 
  rgba(255, 255, 255, 0.5) );
  z-index: 0;
  
}
#app {
  font-family: "Montserrat", sans-serif;
  line-height: 1.4;
}

.title-container{
  text-align: left;
  display: grid;
  align-items: center; 
  width: 80%;
  margin: 375px auto 0 auto;
  padding-left: 30px;

}

#main-title {
  font-size: 2.5rem;
  font-weight: 300;
  text-shadow:2px 3px 8px rgba(32, 46, 59, 0.5);
  animation-name: textEffectTest;
  animation-duration: 7s;
  animation-iteration-count: infinite;
  transition: ease-in-out;
  
}

#main-subtitle {
  font-size: 3.0rem;
  font-weight: 300;
  font-family: 'Raleway', sans-serif;
  text-shadow:5px 2px 8px rgba(32, 46, 59, 0.507);
  line-height:1.4;
}
</style>
