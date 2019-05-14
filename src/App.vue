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
  margin: 375px auto 0 auto;
  padding-left: 30px;

}

#main-title {
  font-size: 2.5rem;
  font-weight: 300;
  text-shadow:2px 3px 8px rgba(32, 46, 59, 0.5);
}

#main-subtitle {
  font-size: 3.0rem;
  font-weight: 300;
  font-family: 'Raleway', sans-serif;
  text-shadow:5px 2px 8px rgba(32, 46, 59, 0.507);
  line-height:1.4;
}
</style>
