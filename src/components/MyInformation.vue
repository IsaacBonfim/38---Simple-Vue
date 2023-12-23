<template>
  <InfoTable />
</template>

<script>
import InfoTable from './InfoTable.vue'

export default {
  name: 'MyInformation',
  components: {
    InfoTable
  },
  props: {
    msg: String
  }
}
</script>

<style>
a {
  color: #42b983;
}
</style>
