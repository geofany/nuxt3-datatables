<template>
  <DataTable :data="[[1, 2], [3, 4]]" class="display">
    <thead>
      <tr>
        <th>A</th>
        <th>B</th>
      </tr>
    </thead>
  </DataTable>
</template>

<script setup lang="ts">
import DataTable from 'datatables.net-vue3'
import DataTablesLib from 'datatables.net';

DataTable.use(DataTablesLib);
</script>

<style scoped></style>