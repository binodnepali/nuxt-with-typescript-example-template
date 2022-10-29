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

<style scoped lang="scss">
div {
  background-color: rgb(38, 38, 38);
  color: #fff;
  padding: 0.2rem;

  ul {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>