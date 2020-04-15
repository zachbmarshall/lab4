<template>
<div id="app">
  <div class="header">
    <router-link to="/">
      <div class="logo">
        <img style="width:200px;height:200px;" src="https://images.vexels.com/media/users/3/134640/isolated/preview/f2755703f8a93785225a13be336ad9c1-laugh-crying-emoji-emoticon-by-vexels.png">
      </div>
    </router-link>
    <div class="title">
      <h1>A place for funny pictures
      </h1>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/admin">Post a picture</router-link>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: rgb(61, 41, 87);
  color: rgb(178, 198, 252);
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 50px;
  padding: 20px 100px 0px 100px;
  background: #e3e3e3;
  font-size: 12px;
}

.footer a {
  color: #000;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
