<style scoped>
  .container {
    //overflow-y: scroll;
    margin-top: 60px;
    width: 320px;
    height: 560px;
    background-image: url('img/715495.jpg');
    background-size: cover;
    border-radius: 10px;
  }
input[type="submit"]{
  margin-top: 25px;
  height: 35px;
  background: rgba(0, 191, 255, 0.6);
  color: #eeffff;
  font-weight: bold;
  font-size: 16px;
}
input[type="submit"]:hover{
  background: rgba(30, 144, 255, 0.6);
  cursor: pointer;
}
.container input[type="text"], .container input[type="password"] {
  background: rgba(255, 255, 255, 0.5);
}
h1 {
  color: #FF6ECF;
  font-size: 3em;
  text-align: center;
}
.block-edge {
  height: 12px;
}
.head{
  position: absolute;
}
.container .input-container {
  margin-top: 30%;
}
.tips {
  text-align: center;
}
</style>

<template>
  <div class="container">
    <div class="input-container">
      <form action="#" method="get" class="form-group">
        <h1>Alice</h1>
        <div class="input-group">
          <span class="input-group-addon">账 号</span>
          <input class="form-control" type="text" autocomplete="off">
        </div>
        <div class="block-edge"></div>
        <div class="input-group">
          <span class="input-group-addon">密 码</span>
          <input class="form-control" type="password" autocomplete="off">
        </div>
        <input type="submit" class="form-control" value="注册" name="register" >
        <div class="block-edge"></div>
        <div class="block-edge"></div>
        <p class="tips">已有账号？<router-link to="/me" class="navbar-link">返回登陆</router-link></p>
      </form>
    </div>
  </div>
</template>
