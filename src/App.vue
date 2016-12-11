<template>
  <div>
    <div class="hero-banner">
      <img class="hero-image" src="./assets/logocrown.png">
      <h1><b>Welcome to the most challenging app, ever.</b></h1>
      <h2>Enchante Your Journey. Break the bad habits.</h2>
    </div>
    <div class="app-description">
      <h2>Ready for a challenge?</h2>
      <h4>Sign up, pick the challenge you want to complete, choose ur friend and name the prize!
      Sign up, pick the challenge you want to complete, choose ur friend and name the prize!Sign up,
      pick the challenge you want to complete, choose ur friend and name the prize!</h4>
    </div>
    <div class="app-images">
      <img class="app-image" src="./assets/signup.png">
      <img class="app-image" src="./assets/logged.png">
      <img class="app-image" src="./assets/request.png">
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

.hero-image {
  /*width: 200px;*/
  height: 300px;
}

.hero-banner {
  background-color: #FF5C5C;
  padding: 50px;
  color: #EDEDED;
  text-align: center;
}

.app-description {
  width: 700px;
  margin: auto;
  padding: 30px;
  text-align: center;
  color: #31323A;
}

.app-images {
  text-align: center;

}
.app-image {
  display: inline-block;
  width: 280px;
  padding: 30px;

}

</style>
