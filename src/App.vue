<template>
<el-container>
    <el-aside>
        <h3>Side Nav</h3>
    </el-aside>
    <el-main>
        <HelloWorld :msg="$t('helloWorld')" />
    </el-main>
</el-container>
</template>

<script lang='ts' setup>

import HelloWorld from './components/HelloWorld.vue';

</script>

<style lang="scss">
#echarts-spa-app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;

    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
}
</style>
