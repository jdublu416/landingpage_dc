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
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
 
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
  margin: 200px auto;
  padding-left: 50px;

}

#main-title {
  font-size: 2.0rem;
  font-weight: 300;
}

#main-subtitle {
  font-size: 2.5rem;
  font-weight: 300;
  font-family: 'Raleway', sans-serif;
}
</style>
