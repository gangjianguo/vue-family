<template>
<div class="el-menu">
    Menu
</div>
</template>
<script setup>
import { ref, onMounted, computed, watch, nextTick } from 'vue'
</script>
<style lang='scss' scoped>
@include b(menu){
    min-width: 200px;
    border-right: 1px solid #ccc;
    height: 100%;
}
</style>