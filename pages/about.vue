<template>
    <div>
    
<h2>About</h2>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga recusandae omnis doloribus fugit nostrum est porro. Reprehenderit recusandae fugit voluptates.</p>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga recusandae omnis doloribus fugit nostrum est porro. Reprehenderit recusandae fugit voluptates.</p>
    <div>{{data}}</div>
    </div>
</template>

<script setup>
const {data} = await useFetch('/api/currency/CAD')

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