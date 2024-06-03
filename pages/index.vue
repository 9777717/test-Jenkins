<script setup lang="ts">

</script>
<template>
    <div>
        <H1>Test Nuxt</H1>
        <div>
            <p>1</p>
            <p>2</p>
            <p>3</p>
            <p>4</p>
            <p>5</p>
            <p>6</p>
            <p>7</p>
            <p>8</p>
            <p>9</p>
        </div>
        <h2>jenkins test</h2>
        <div>
            <p v-for="item,index in 'jenkins'" :key='index'>{{ item }}</p>
        </div>
    </div>
</template>

<style lang="scss" scoped></style>