<template>
  <div class="pagecontent">
    
    <div class="content-pagecontent">
      <div class="content-left">
        <Cards class="cards-content"/>
        <TransactionHistory class="transhisto-content"/>
      </div>
      <div class="content-right">
        <Pricing class="pricing-content"/>
        <Stats class="stats-content"/>
        <NewTransaction class="newtransac-content"/>
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
    justify-content: space-between;
    margin-right: 15px;
    /* grid-template-rows: 1fr 1fr 1fr; */
  }
  .cards-content, .transhosto-content {
    height: 50%;
  }
  .pricing-content, .stats-content {
    height: 35%;
  }
  .newtransac-content {
    height: 20%;
  }
  .content-right {
    width: 50%;
    display: flex;
    float: right;
    flex-direction: column;
    margin-left: 15px;
    justify-content: space-around;
  }
  h4 {
  font-family: Suprema;
  font-style: normal;
  font-weight: 600;
  font-size: 20.1118px;
  line-height: 25px;
  margin: 10px 0;
  }
</style>
