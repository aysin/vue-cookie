<template>
  <div>
    <head>
      <meta charset="utf-8">
      <link href="/static/faviconcrown.ico" rel="shortcut icon" type="image/x-icon" />
      <title>Optimus</title>
    </head>
    <navbar></navbar>
    <div class="hero-banner">
      <img class="hero-image" src="./assets/logocrown.png">
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
        <img class="app-image" src="./assets/signup.png">
        <p>Simply login with your Facebook account.</p>
      </div>
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/logged.png">
        <p>Great! Go ahead and create your first challenge!</p>
      </div>
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/challengeview.png">
        <p>Now pick your something you want to achieve!.</p>
      </div>
      <div class="app-image-wrapper">
        <img class="app-image" src="./assets/overview.png">
        <p>You are set! Fire away your request!.</p>
      </div>

    </div>
    <!-- this part is info about the company -->
    <div class="app-description">
      <div class="app-banner">
        <h2 class="app-text"><a name="about">About</a></h2>
        <about></about>
        <img class="about-image" src="./assets/aysin.png">
        <img class="about-image" src="./assets/arthur.png">
      </div>
    </div>
    <!-- Contact info footer -->
    <footer class="footer">
      <h2 class="app-text"><a name="contact"></a>
        <contact>
        </contact>
      </h2>
    </footer>
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

.app-image-wrapper {
  display: inline-block;
  width: 220px;
  padding: 60px;
}

.app-image {
  /* Image inherits the parent size which is the app-image-wrapper*/
  width: 100%;
}

.about-image {
  width: 220px;
  padding: 60px;
}
.app-text {
  font-weight: normal;
}

.footer {
  background: #FF5C5C;
  color: #EDEDED;
  padding: 10px 40px 20px;
}

</style>
