<template>
  <div class="pagecontent">
    
    <div class="content-pagecontent">
      <div class="content-left">
        <Cards />
        <TransactionHistory />
      </div>
      <div class="content-right">
        <Pricing />
        <Stats />
        <NewTransaction />
      </div>
    </div>
  </div>
</template>


<script>
import Cards from '@/components/Cards.vue'
import TransactionHistory from '@/components/TransactionHistory.vue'
import Pricing from '@/components/Pricing.vue'
import Stats from '@/components/Stats.vue'
import NewTransaction from '@/components/NewTransaction.vue'

export default {
  name: 'PageContent',
  components: {
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
  .pagecontent {
    display: flex;
    flex-direction: column;
    
  }
  .content-pagecontent {
    display: flex;
  }
  .content-left {
    width: 50%;
    display: flex;
    float: left;
    flex-direction: column;
  }
  .content-right {
    width: 50%;
    display: flex;
    float: right;
    flex-direction: column;
  }
</style>

<style>
  h4 {
  font-size: 1.8rem;
  font-weight: normal;
  margin: 0;
  }
</style>
