<script setup lang="ts">

</script>

<template>
  <div>
    <van-nav-bar 
      
        left-text="返回" 
        left-arrow 
        title="商品信息"
        @click-left="$router.back()" 
        />
        <h3>基本信息</h3>

  <van-cell-group>
    <van-cell title="单元格" value="内容" />
    <van-cell title="单元格" value="内容" />
    <van-cell title="单元格" value="内容" />
    <van-cell title="单元格" value="内容" />
    <van-cell title="单元格" is-link value="内容" />
    <van-cell title="单元格" is-link value="内容" />
    <van-cell title="单元格" is-link value="内容" />
  </van-cell-group>

  <h3>添加照片</h3>

  <h3>商品描述</h3>
  <textarea cols="20" rows="5"></textarea>

  <!-- <van-button type="warning" @click="$router.push('/sellbook/book2')">出价</van-button> -->
  </div>
</template>

<style lang="scss" scoped>
h3{
  color: rgb(214, 138, 75);
}
</style>