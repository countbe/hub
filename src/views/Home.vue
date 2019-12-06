<template>
  <div class="home">
      <div class="top">
          <h1>多加网</h1>
        <input type="text" placeholder="热门搜索">
      </div>
        <div class="swiper">
            <template>
                <el-carousel  indicator-position="outside">
                <el-carousel-item v-for="item in 4" :key="item">
                    <h3>{{item}}</h3>
                </el-carousel-item>
                </el-carousel>
            </template>
        </div>
        <div class="main">
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
            <dl>
                <dt></dt>
                <dd>成单奖励</dd>
            </dl>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.home{
    width: 100%;
    height: 667px;
    background: cadetblue;
}
h1{
    margin-left: 150px;
}
input{
    width: 220px;
    height: 30px;
    margin-left: 100px;
    border-radius: 15px;
    border: 1px solid #ffff;
}
.el-carousel__item h3{
    color: #ccc;
    font-size: 18px;
    opacity: 0.75;
    line-height: 150px;
    margin: 0;
}
.el-carousel__item:nth-child(2n){
    background-color: #99a9bf;
}
.el-carousel__item:nth-child(2n+1){
    background-color: #d3dce6;
}
dt{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: orange;
}
.main{
    margin-left: 10px;
    width: 100%;
    /* height: 80px; */
    display: flex;
    flex-wrap: wrap;
}
.main dl{
    width: 25%;
}
</style>