<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">移动端唤醒相机拍照/图片预览/上传</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
