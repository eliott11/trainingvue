<template>
  <div>
    <Menu />
    <Content />
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Content from './components/Content.vue'


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
}

</style>
