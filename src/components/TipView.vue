<script setup>
import InputForm from "./InputForm.vue";
import BillControlMain from "./BillControlMain.vue";
</script>

<template>
  <div class="container">
    <input-form />
    <bill-control-main />
  </div>
</template>

<style scoped>
.container {
  display: flex;
}
</style>