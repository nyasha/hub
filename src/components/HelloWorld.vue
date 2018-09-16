<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Join Now</h2>
    <ul>
      <li>
        <a
          href="https://facebook.com/techhubharare"
          target="_blank"
        >
          Facebook
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/hararehub"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <li>
        <a
          href="https://discordapp.com/channels/427674720574636042/427674720574636044"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="https://docs.google.com/forms/d/1faE1qlgFgvN3dLPqmsxlDh5qWMT_7LY0NCLFmsjBFVM"
          target="_blank"
        >
          Sign Up
        </a>
      </li>
      <br>
      <li>
        <a
          href="https://docs.google.com/forms/d/1faE1qlgFgvN3dLPqmsxlDh5qWMT_7LY0NCLFmsjBFVM"
          target="_blank"
        >
          Sign Up
        </a>
      </li>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to our Entrepreneurship club"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
