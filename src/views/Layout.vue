<template>
  <div class="home">
    <Bar />
    <Menu />
  </div>
</template>

<script>
import Bar from "../components/layout/Bar.vue";
import Menu from "../components/layout/Menu.vue";

export default {
  name: "Home",
  components: {
    Bar,
    Menu
  }
};
</script>
