<template>
  <div class="pagecontent">
    <Header />
    <div class="content-pagecontent">
      <ContentLeft />
      <ContentRight />
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import ContentLeft from '@/components/ContentLeft.vue'
import ContentRight from '@/components/ContentRight.vue'

export default {
  name: 'PageContent',
  components: {
    Header,
    ContentLeft,
    ContentRight
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .pagecontent {
    display: flex;
    width: 100%;
    flex-direction: column;
    padding: 0 45px 0 45px;
  }
  .content-pagecontent {
    display: flex;
  }
</style>
