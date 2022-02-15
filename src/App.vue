<template>
  <div class="page"> <!--- page including all content --->
    <Menu/>
    <div class="margin-content"> <!--- content --->
      <Header />
      <Content />
    </div>
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import './assets/index.scss'

export default {
  name: 'App',
  components: {
    Menu,
    Header,
    Content
  }
}
</script>

<style scoped>
.page { /* display page */
  display: flex;
  /* max-height: 100vh;
  overflow: auto; */
}
.margin-content { /* margin content */
  padding: 0 30px 0 30px;
  flex-grow:1;
}
</style>
