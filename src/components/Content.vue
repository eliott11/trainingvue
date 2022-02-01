<template>
  <div>
    <Header />
    <Cards />
    <TransactionHistory />
    <Pricing />
    <Stats />
    <NewTransaction />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Cards from '@/components/Cards.vue'
import TransactionHistory from '@/components/TransactionHistory.vue'
import Pricing from '@/components/Pricing.vue'
import Stats from '@/components/Stats.vue'
import NewTransaction from '@/components/NewTransaction.vue'

export default {
  name: 'Content',
  components: {
    Header,
    Cards,
    TransactionHistory,
    Pricing,
    Stats,
    NewTransaction
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  template {
    display: flex;
    float: right;
  }
  div {
    align-items: flex-start;
    flex-direction: column;
    margin-left: 10px;
  }
</style>
