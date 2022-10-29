<template>
  <div>
    <ul>
      <li>Copyright - {{ date.getFullYear() }}</li>
    </ul>
  </div>
</template>

<script setup lang="ts">
const date = ref(new Date());
</script>
