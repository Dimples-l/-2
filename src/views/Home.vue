<template>
  <div class="nav">
    <div class="web-title">hy</div>
    <div class="nav1">
      <ul><router-link to="/">首页</router-link></ul>
      <ul><router-link to="">登录</router-link></ul>
      <ul><router-link to="">注册</router-link></ul>
      <ul><router-link to="">收藏</router-link></ul>
      <ul><router-link to="">我的</router-link></ul>
    </div>
    <div class="search">
      <input type="text" name="search" id="search">
      <button>搜索</button>
    </div>
  </div>
</template>

<style>
  a{
    color: grey;
    text-decoration: none;
  }
  .nav{
    position: relative;
    background-color: black;
    opacity: 0.7;
    height: 82px;
  }
  .web-title{
    position: absolute;
    font-size:50px;
    color: white;
    margin-left: 10%;
  }
  .nav1{
    position: relative;
    text-align: right;
    width: 600px;
  }
  ul{
    display: inline;
  }
  .search{
    margin-top: 30px;
    margin-left: 30px;
  }
  #search{
    border-radius: 10px;
  }
  button{
    border: none;
    border-radius: 8px;
    /* background-color: cornflowerblue; */
    margin-left: 10px;
  }
</style>

<script>
export default {
  data(){
    return {}
  }
}

</script>