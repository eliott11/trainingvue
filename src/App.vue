<template>
  <Menu />
  <Header />
  <Cards />
  <TransactionHistory />
  <Pricing />
  <Stats />
  <NewTransaction />
</template>

<script>
import Menu from './components/Menu.vue'
import Header from './components/Header.vue'
import Cards from './components/Cards.vue'
import TransactionHistory from './components/TransactionHistory.vue'
import Pricing from './components/Pricing.vue'
import Stats from './components/Stats.vue'
import NewTransaction from './components/NewTransaction.vue'

export default {
  name: 'App',
  components: {
    Menu,
    Header,
    Cards,
    TransactionHistory,
    Pricing,
    Stats,
    NewTransaction
  }
}
</script>

<style>
h3 {
    color: #0B80D8;
    margin: 1em;
}
</style>
