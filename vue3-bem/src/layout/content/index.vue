<template>
    <div class="el-content">
        <div v-for="item in 100" class="el-content__items">{{ item }}</div>
    </div>
</template>
<script setup>
import { ref, onMounted, computed, watch, nextTick } from 'vue'
</script>
<style lang='scss' scoped>
@include b(content) {
    flex: 1;
    overflow: scroll;
    @include e(items){
        padding: 10px;
        margin: 10px;
        border: 1px solid #ccc;
        // 给 div 元素设置边框圆角
        border-radius: 4px;
    }
}
</style>