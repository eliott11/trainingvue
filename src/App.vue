<template>
<head>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Dongle">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">
</head>
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

template {
  font-family: "Dongle";
}

</style>
