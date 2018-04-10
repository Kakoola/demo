
<style scoped>
*{
  margin:0;
  padding: 0;
}
h1{
  border:1px solid yellow;
}
.user {
  width: 200px;
  /* border:1px red solid; */
  position: relative;
}
.user-icon {
  position: absolute;
  width: 20px;
  height: 20px;
  top:3px;
  left:2px;
  background-image: url("~assets/accout.png");
  background-repeat: no-repeat;
  background-position: 0px 0px;
  /* border: solid 1px blue; */
}
.import {
  padding-left: 20px;
  border:1px pink solid;
  height: 20px;
}
</style>
<template>
  <div>
    <h1>登录页面</h1>
    <div class="user">
      <label for="import">
        <i class="user-icon"></i>
      </label>
      <input class="import" type="text" placeholder="帐号">
    </div>
    <br>
    <!-- <input type="password" placeholder="密码"> -->
  </div>
</template>
