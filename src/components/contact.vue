<template>
  <div>
    <a class="info" href="mailto:optimus@gmail.com"><h3>Contact us: team@optimusapp.com<h3></a>
    <!-- Begin MailChimp Signup Form -->
    <link href="//cdn-images.mailchimp.com/embedcode/horizontal-slim-10_7.css" rel="stylesheet" type="text/css">
    <div class="subscription-style">
      <form action="//optimusapp.us15.list-manage.com/subscribe/post?u=c111cc44f29731da1dd622cfb&amp;id=ed8567c769" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <p class="subscription-text" for="mce-EMAIL">Want to hear from us?</p>
        <input type="email" value="" name="EMAIL" class="email"  placeholder="email address" required>
          <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
          <!-- <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_c111cc44f29731da1dd622cfb_ed8567c769" tabindex="-1" value=""></div> -->
        <input type="submit" value="Subscribe" name="subscribe">
      </form>
    </div>
  </div>
</template>


<script>
export default {
  name: 'contact',
}
</script>



<style scoped>

.info {
  color: inherit;
  text-decoration: none;
  display: block;
  margin: 0px;
  text-align: center;
}
.subscription-style{
    padding: 10px 30px;
    color: #EDEDED;
    text-align: center;
}


</style>
