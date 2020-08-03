<template>
  <div id="app">
    <Layout />
  </div>
</template>
<script>
import Layout from "@/views/Layout.vue";

export default {
  components: {
    Layout
  }
};
</script>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-size: 14px;
  color: #6c5f57;
  min-width: 960px;
}
a {
  text-decoration: none;
}
input {
  outline: none;
}
li {
  list-style: none;
}
</style>
