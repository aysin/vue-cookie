<template>
  <div>
    <div class="hero-banner">
      <img class="hero-image" src="./assets/logocrown.png">
      <h1 class="hero-text">Welcome to the most challenging app, ever.</h1>
      <h2 class="hero-text">Enchante Your Journey. Break the bad habits.</h2>
    </div>
    <div class="app-description">
      <div class="app-banner">
        <h2 class="app-text">Ready for a challenge?</h2>
        <h4 class="app-text">Sign up, pick the challenge you want to complete, choose ur friend and name the prize!
        Sign up, pick the challenge you want to complete, choose ur friend and name the prize!Sign up,
        pick the challenge you want to complete, choose ur friend and name the prize!</h4>
      </div>
    </div>
    <div class="app-images">
      <img class="app-image" src="./assets/signup.png">
      <img class="app-image" src="./assets/logged.png">
      <img class="app-image" src="./assets/requested.png">
    </div>
    <div class="hero-banner">
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

<style>
body{
  margin: 0px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}

/* you can assign all of them to have same style*/
/*h1, h2, h3, h4, h5, h6 {
  font-weight: lighter;
}*/

.hero-image {
  /*width: 200px;*/
  height: 300px;
}

.hero-banner {
  background-color: #FF5C5C;
  padding: 50px;
  color: #EDEDED;
  text-align: center;
  background-image: linear-gradient(to bottom,#FF5C5C 0,#f98181 100%);
}

.hero-text {
  font-weight: normal;
}

.app-banner {
  width: 700px;
  margin: auto;

}

.app-description {
  background-color: #EDEDED;
  padding: 30px;
  text-align: center;
  color: #31323A;
}

.app-images {
  text-align: center;
}

.app-image {
  display: inline-block;
  width: 220px;
  padding: 60px;

}

.app-text {
  font-weight: normal;
}

</style>
