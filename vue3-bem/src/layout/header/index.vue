<template>
    <div class="el-header">
        Header
    </div>
</template>
<script setup>
import { ref, onMounted, computed, watch, nextTick } from 'vue'
</script>

<style lang='scss' scoped>
@include b(header){
    height: 60px;
    // 设置底部边框样式
    border-bottom: 1px solid #ccc;
}
</style>