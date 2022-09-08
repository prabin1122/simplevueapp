<template>
  <div id="app">
    <Header/>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>
<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header
  }
};
</script>

<style>
body {
  background: #ffffff;
}
.container {
  max-width: 900px;
}
.card {
  background: #000000;
  box-shadow: 12px 2px 10px #000;
}
.card-body {
  color: #f9ffee;
}
.card-body a {
  color: #ffffff;
}
.card-body a:hover {
  color: rgb(213, 213, 213);
  text-shadow: 2px 2px 22px white;
  text-decoration: none;
}
</style>
