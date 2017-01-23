<template>
  <nav>
  	<ul>
      <!-- fix them w css, by removing the dots and aligning them 'list-style-type check this' -->
  		<!-- <li><a href="#home">Home</a></li> -->
  		<li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
  	</ul>
  </nav>
</template>


<script>
export default {
  name: 'navbar',
}
</script>


<style scoped>
ul {
    list-style-type: none;
    margin: 10;
    padding: 0px 10px 10px 10px;
}

li {
    display: inline;
    padding: 20px;
}

a {
  color: #31323A;
  text-decoration: none;
  margin-right: 30px;
  width: 30px;
  height: 30px;
  /*-webkit-transition: all 1.5s ease;*/
  text-align: center;
}

a:hover {
	background: #EDEDED;
}
</style>
