<template>
  <div class="nav">
    <div class="web-title">hy</div>
    <div class="nav1">
      <span><router-link to="/">首页</router-link></span>
      <span><router-link to="">登录</router-link></span>
      <span><router-link to="">注册</router-link></span>
      <span><router-link to="">收藏</router-link></span>
      <span><router-link to="">我的</router-link></span>
    </div>
    <div class="search">
      <input type="text" name="search" id="search">
      <button>搜索</button>
    </div>
  </div>

  <!-- <router-view /> -->
  
</template>



<style>
*{
  margin: 0;
  padding: 0;
}
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
    float: left;
    top:10px;
  }
  .nav1{
    /* position: relative; */
    text-align: right;
    width: 600px;
    float: left;
    margin-top: 30px;
    left: 100px;
  }
  span{
    margin-left: 50px;
  }
  .search{
    margin-top: 30px;
    margin-left: 30px;
    float: left;
  }
  #search{
    border-radius: 10px;
    width: 300px;
    height: 20px;
  }
  button{
    border: none;
    border-radius: 5px;
    margin-left: 10px;
  }
</style>

<script>
// import content from './components/content'
export default {
  data(){
    return {
      
    }
  }
}
</script>