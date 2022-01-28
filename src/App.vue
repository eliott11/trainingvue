<template>
<head>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Dongle">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">
</head>
  <Menu />
  <!-- <Content /> -->
  <Header />
</template>

<script>
import Menu from './components/Menu.vue'
// import Content from './components/Content.vue'
import Header from './components/Header.vue'


export default {
  name: 'App',
  components: {
    Menu,
    // Content,
    Header,
  }
}
</script>

<style scoped>
template {
  font-family: "Dongle";
  display: flex;
}

</style>
