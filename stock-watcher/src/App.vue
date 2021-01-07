<template>
  <header>
    <h1>Add Stock</h1>
  </header>
  <AddStock/>
  <Stocks/>
</template>

<script>
import AddStock from './components/AddStock.vue'
import Stocks from './components/Stocks.vue'

export default {
  name: 'App',
  components: {
    AddStock,
    Stocks
  }
}
</script>

<style>
</style>
