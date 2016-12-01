<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Bird &lt;3 {{ bird }}</h2>
    <button v-on:click="onClick">{{ counter }}</button>
  </div>
</template>

<script>
import cookie from './thibaut'
console.log(cookie(10))

export default {
  name: 'hello',
  data: () => {
    return {
      msg: 'Welcome to Your Challenge Cookie App',
      bird: 'Cookie',
      counter: 0
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
