<template>
  <div id="app">
   
    <TableItem /><br>
    <TbItem />
    <TransFrom />
    <FlexItem />
  </div>
</template>

<script>
import TableItem from './components/TableItem'
import TbItem from './components/TbItem'
import TransFrom from './components/TransFrom'
import FlexItem from './components/FlexItem'


export default {
  name: 'App',
  components: {
    TableItem,
    TbItem,
    TransFrom,
    FlexItem
  }
}
</script>

<style>

</style>
