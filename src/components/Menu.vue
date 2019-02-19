<template>
  <ul>
    <li>
      <router-link to="contact">Contact</router-link>
    </li>
    <li>
      <router-link to="/">HelloWorld</router-link>
    </li>
  </ul>
</template>

<script>
export default {
  name: 'Menu-header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  color:red;
}
a {
  color:red;
}
</style>
