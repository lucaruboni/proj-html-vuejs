<script>
import PageHeader from './components/PageHeader.vue';
import PageMain from './components/PageMain.vue';
import PageFooter from './components/PageFooter.vue';
import infos from './components/data/nexgen_header.json';

export default{
  components: {
    PageHeader,
    PageMain,
    PageFooter
  },
  data(){
    return{
      infos: infos
    }
  }
}


</script>

<template>

  <PageHeader></PageHeader>

  <PageMain></PageMain>

  <PageFooter v-for="info in infos" :open_hours="info.open_hours" :cell_number="info.cell_number" :email="info.email" :about="info.about" :address="info.address" :transport="info.transport" :support="info.support"></PageFooter>

</template>

<style scoped>

</style>
