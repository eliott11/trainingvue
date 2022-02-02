<template>
  <div class="content-left">
    <Cards />
    <TransactionHistory />
  </div>
</template>

<script>
import Cards from '@/components/Cards.vue'
import TransactionHistory from '@/components/TransactionHistory.vue'

export default {
  name: 'ContentLeft',
  components: {
    Cards,
    TransactionHistory,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .content-left {
    width: 50%;
    display: flex;
    float: left;
    flex-direction: column;
  }
</style>
