<template>
    <div class="el-box">
        <div><Menu></Menu></div>
        <div class="el-box__right">
            <Header></Header>
            <Content></Content>
        </div>
    </div>
</template>
<script setup>
import { ref } from 'vue'
import Content from '../layout/content/index.vue'
import Header from '../layout/header/index.vue'
import Menu from '../layout/menu/index.vue'

</script>
<style lang='scss' scoped>
@include b(box) {
    height: 100%;
    // 弹性盒子，默认从左到右排列
    display: flex;
    @include e(right){
        display: flex;
        flex-direction: column;
        flex: 1;
    }
}
</style>