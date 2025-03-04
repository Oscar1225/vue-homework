<template>
   <div class="container">
        <h2>SUPER PAGOS</h2>
        <h2 class="beta">beta test</h2>
    </div>
</template>

<script lang="ts">
export default {
  name: 'ContainerComponent', // 更新為多個單詞
};
</script>

<style scoped>
  .container {
    display: flex;
    justify-content: space-between;
    border-radius: 8px;
    margin-left: 10px;
    margin-right: 10px;
  }
  .beta{
    border:5px;
    background-color: deepskyblue;
    border-radius: 5px;
    width: 100px;
  }
</style>
