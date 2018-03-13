<template>
  <q-page class="flex flex-center">
    <q-input float-label="Search:" :value="queryText"/>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      queryText: ''
    }
  }
}
</script>
