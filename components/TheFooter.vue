<template>
  <div>
    <ul>
      <li>Copyright - {{ date.getFullYear() }}</li>
    </ul>
  </div>
</template>

<script setup lang="ts">
const date = ref(new Date())

console.log(date.value)
</script>

<style scoped lang="scss">
div {
  background-color: black;
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
