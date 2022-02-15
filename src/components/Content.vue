<template>
  <div class="pagecontent"> <!--- page --->
    <div class="content-pagecontent"> <!--- content --->
      <div class="content-left"> <!--- content left --->
        <Cards class="cards-content"/>
        <TransactionHistory class="transhisto-content"/>
      </div>
      <div class="content-right"> <!--- content right --->
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
  .pagecontent { /* content general */
    display: flex;
    flex-direction: column;
  }
  .content-pagecontent { /* content in page */
    display: flex;
  }
  .content-left {  /* content left */
    width: 50%;
    height: 85vh;
    display: flex;
    float: left;
    flex-direction: column;
    justify-content: space-between;
    margin-right: 5px;
    /* grid-template-rows: 1fr 1fr 1fr; */
  }
  .cards-content, .transhisto-content { /* content left height */
    height: 50%;
  }
  .pricing-content, .stats-content { /* content right height */
    height: 35%;
  }
  .newtransac-content { /* content right height */
    height: 30%;
  }
  .content-right { /* content right display & width */
    width: 50%;
    display: flex;
    float: right;
    flex-direction: column;
    margin-left: 5px;
    justify-content: space-between;
  }
  /* *, ::after, ::before {
    box-sizing: initial;
  } */
</style>
