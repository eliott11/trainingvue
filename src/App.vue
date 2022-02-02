<template>
  <div>
    <Menu />
    <Content />
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Content from './components/PageContent.vue'


export default {
  name: 'App',
  components: {
    Menu,
    Content
  }
}
</script>

<style scoped>
div {
  font-family: "Dongle";
  display: flex;
  /* max-height: 100vh;
  overflow: auto; */
}
</style>
