<template>
    <div>
        <h2>About</h2>
        <p>This is the testing</p>
        <div>{{data}}</div>
    </div>
</template>

<script setup>
    const { data} = await useFetch('/api/ninja')
</script>

<style scoped>
 h2{
    margin-bottom: 20px;
    font-size: 36px;
 }
 p{
    margin: 20px 0;
 }
</style>