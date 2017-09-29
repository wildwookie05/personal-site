<template>
  <section>
    <div class="container-head">
      <img src="https://i.imgur.com/RWYP45f.png" class="profile">
      <div class="nav">
        <div class="nav-menu">
          one | two | three
        </div>
      </div>
    </div>
    <div class="container-body">
      <div class="menu">
      </div>
      <div class="body">
        <div style="border-bottom:1px solid; height:33px;width:90%;">
          <h2 class="title">
            About
          </h2>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.container-head{
  display: flex;
  width:100%;
  height:auto;
  justify-content: center;
}
.container-body{
  display: flex;
  width:100%;
  height:100%;
  justify-content: center;
}
.menu{
  width:20%;
  height:100px;
}
.body{
  display:flex;
  justify-content: center;
  width:55%;
  height:100px;
}
.nav{
  display:flex;
  justify-content: center;
  width:55%;
  height:auto;
  text-align:right;
}
.nav-menu{
  width:90%;
  position:relative;
  top:50%;
  transform: translateY(-18px);
}
.title{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 200;
  font-size:30px;
  letter-spacing: 5px;
}

.grey{ 
  background-color:gray;
}
.blue{
  background-color:blue;
}
.red{
  background-color:red;
}
.profile{
  width:20%;
  height:20%;
}
</style>
