<template>
<div id="app">
  <div class="header">
    <router-link to="/">
      <div class="logo">
        <img src="/logo.png">
      </div>
    </router-link>
    <div class="title">
      <h1>Car Tracker</h1>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/admin">Admin</router-link>
    <p></p>
    <a href="https://github.com/maxaham/Car-Tracker/blob/master/tutorials/1-installing-packages.md"> Repository</a>
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
  color: white;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #FFFFFF;
  color: #1C454F;
}

.header img {
  width: 95px;
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
  background-image: url("/back.jpg");
  background-position: center;
  background-size: cover;
  background-color: black;
}

/* Footer */
.footer {
  /*position: absolute;
  bottom: 0;
  margin: 0 auto;
  width: 100%;*/
  height: 70px;
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
