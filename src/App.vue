<template>
<el-container>
    <el-aside>
        Side Nav
    </el-aside>
    <el-main>
        <HelloWorld msg="Hello World" />
    </el-main>
</el-container>
</template>

<script lang='ts' setup>

import HelloWorld from './components/HelloWorld.vue';

</script>

<style scoped lang="scss">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>