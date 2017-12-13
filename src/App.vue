<template>
  <div>
    <head>
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta charset="utf-8">
      <link href="/static/faviconcrown.ico" rel="shortcut icon" type="image/x-icon" />
      <title>Optimus</title>
    </head>
    <navbar></navbar>
    <div class="hero-banner">
      <img class="hero-image" src="./assets/optimustxt.png">
      <h1 class="hero-text">Welcome to the most challenging app, ever.</h1>
      <h2 class="hero-text">Enchant your journey. Break the bad habits.</h2>
    </div>
    <div class="app-description">
      <div class="app-banner">
        <h2 class="app-text">Ready for a challenge?</h2>
        <h4 class="app-text">
          Have you ever started a New Year’s Resolution or wanted to achieve something
          in your life but failed to complete it? We have a simple yet powerful
          hypothesis: If you would have had a friend who challenged you to finish your task, you would have made it!</h4>
        <h4 class="app-text">
          All you need is motivation and some support along the way!
          This is your chance: Download the Optimus app for your smartphone to complete all your
          resolutions and <b>break all the bad habits!</b> We’ve got your back!</h4>
      </div>
    </div>
    <div class="app-images">
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/login.png">
        <p>Great! Go ahead and create your first challenge!</p>
      </div>
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/challengelist.png">
        <p>Now pick your something you want to achieve!.</p>
      </div>
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/overview.png">
        <p>You are set! Fire away your request!.</p>
      </div>
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/famouschallenge.png">
        <p>or Join to famous influencers' challenges!</p>
      </div>

    </div>
    <!-- this part is info about the company -->
    <div class="app-description">
      <div class="app-banner">
        <h2 class="app-text"><a name="about">About</a></h2>
        <about></about>
        <a class="info" href="mailto:team@optimusapp.com"><p><b>Contact us: team@optimusapp.com</b></p></a>
        <img class="about-image" src="./assets/aysin.png">
        <img class="about-image" src="./assets/arthur.png">
      </div>


</template>


<script>
import navbar from 'components/navbar'
import about from 'components/about'
import contact from 'components/contact'
export default {
  name: 'app',
  components: {navbar: navbar, about: about, contact: contact},
}
</script>

<style>
body{
  margin: 0px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 20px;
}

/* you can assign all of them to have same style*/
/*h1, h2, h3, h4, h5, h6 {
  font-weight: lighter;
}*/

.info {
  color: inherit;
  text-decoration: none;
  display: block;
  margin: 0px;
  text-align: center;
}
.subscription-style{
    /*padding: 10px 30px;*/
    color: #50E3C2;
    text-align: center;
}

.hero-image {
  /*width: 500px;*/
  max-height: 600px;
  width: auto ;
  max-width: 100% ;
  height: auto ;
}

.hero-banner {
  background-color: #50E3C2;
  padding: 50px;
  text-align: center;
  background-image: linear-gradient(to bottom,#50E3C2 0,#FFFFFF 100%);
}

.hero-text {
  font-weight: normal;
}

.app-banner {
  max-width: 700px;
  margin: auto;

}

.app-description {
  background-color: #FFFFFF;
  padding: 30px;
  text-align: center;
  color: #31323A;
}

.app-images {
  text-align: center;
}

.app-image-wrapper {
  display: inline-block;
  max-width: 220px;
  padding: 60px;
}

.app-image {
  /* Image inherits the parent size which is the app-image-wrapper*/
  width: 100%;
}

.about-image {
  max-width: 220px;
  padding: 60px;
}
.app-text {
  font-weight: normal;
}

.footer {
  background: #50E3C2;
  color: #EDEDED;
  padding: 10px 40px 20px;
}

</style>
