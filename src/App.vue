<template>
    <div class="block">
        <span class="demonstration">默认Hover指示器触发</span>
        <el-carousel height="150px">
        <el-carousel-item v-for="item in 4 " :key="item">
        </el-carousel-item>
        </el-carousel>
    </div>
</template>


<script>
export default {

}
</script>

<style>
    .el-carousel_item h3{
        color: #475669;
        font-size: 14px;
        opacity: 0.75;
        line-height: 150px;
        margin: 0;
    }
    .el-carousel_item:nth-child(2n){
        background-color: #99a9bf;
    }
    .el-carousel_item:nth-child(2n+1){
        background-color: #d3dce6;
    }
</style>