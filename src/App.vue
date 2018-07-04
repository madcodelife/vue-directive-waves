<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <div v-waves class="box">我是方按钮</div>
    <div v-waves class="circle">我是圆按钮</div>
    <div v-waves class="circle bCircle">我是大圆按钮</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.box {
  width: 106px;
  height: 38px;
  font-size: 14px;
  background: #66b1ff;
  color: #fff;
  border-radius: 4px;
  cursor: pointer;
  line-height: 38px;
  margin: 0 auto;
}

.circle {
  width: 95px;
  height: 95px;
  font-size: 14px;
  background: #67c23a;
  color: #fff;
  border-radius: 50%;
  cursor: pointer;
  line-height: 95px;
  margin: 0 auto;
  margin-top: 30px;
}

.bCircle {
  background: #e6a23c;
  width: 500px;
  height: 500px;
  line-height: 500px;
}
</style>
