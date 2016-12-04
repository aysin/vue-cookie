<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2><b>Enchante Your Journey!</b></h2>
    <!-- <button @click="onClick">{{ counter }}</button> -->
  </div>
</template>

<script>
export default {
  name: 'hello',
  data: () => {
    return {
      msg: 'Welcome to the most challenging app, ever.'
    }
  },
  methods: {
    onClick: function () {
      this.counter++
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
button {
  font-size: 1.5em;
  color: inherit;
  font-family: inherit;
  border: 1px solid #EEE;
  background: #FFF;
  padding:
}
</style>
