<template>
  <div>
    <!-- <a class="info" href="mailto:team@optimusapp.com"><p class="subscription-text">Contact us: team@optimusapp.com</p></a> -->
    <!-- Begin MAilLite Signup Form -->
    <!-- <form @submit="submit" action="//app.mailerlite.com/webforms/submit/g0l3l9" data-id="271897" data-code="g0l3l9" method="POST" target="_blank">
    	<div class="info">
        <div>
          <p>Keep in touch! We will let you know when&nbsp;the app is released.</p>
  		  </div>
        <div>
      			<input v-model="email" type="text" name="fields[email]" placeholder="Email*" value="">
            <button type="submit">Subscribe</button>
				</div>
    	</div>
    </form> -->
  </div>
</template>



<script>
export default {
  name: 'contact',
  methods: {
    submit: event => {
      event.preventDefault()
      fetch('https://api.mailerlite.com/api/v2/', {method: 'POST'})
    },
  },
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
    /*padding: 10px 30px;*/
    color: #EDEDED;
    text-align: center;
}


</style>
