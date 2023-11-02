<template>
    <div class="page text-light">
      <div class="container">
        <div class="col-lg-6 offset-lg-3">
          <regForm></regForm>
        </div>
      </div>
      <regTable></regTable>
      <MainFooter></MainFooter>
    </div>
</template>

<style>
html body{
  background-color: #343a40;
}
</style>
<script>
import regForm from './components/regForm.vue';
import regTable from './components/regTable.vue';
import MainFooter from './components/MainFooter.vue';

export default {
  components: {regForm, regTable, MainFooter}
}
</script>
