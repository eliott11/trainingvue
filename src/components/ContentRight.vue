<template>
  <div class="content-right">
    <Pricing />
    <Stats />
    <NewTransaction />
  </div>
</template>

<script>
import Pricing from '@/components/Pricing.vue'
import Stats from '@/components/Stats.vue'
import NewTransaction from '@/components/NewTransaction.vue'

export default {
  name: 'ContentRight',
  components: {
    Pricing,
    Stats,
    NewTransaction
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .content-right {
    width: 50%;
    display: flex;
    float: right;
    flex-direction: column;
  }
</style>
