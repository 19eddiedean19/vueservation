<template>
  <v-row justify="center" dense no-gutters>
    <v-col cols="12" md="9" lg="8" xl="6">
      <catalogItemList></catalogItemList>
    </v-col>
  </v-row>
</template>

<script>
import catalogItemList from '@/components/catalog/catalogItem/ciList'

export default {
  components: {
    catalogItemList
  },
  created() {
    //console.log(this)
  }
}
</script>

<style></style>
