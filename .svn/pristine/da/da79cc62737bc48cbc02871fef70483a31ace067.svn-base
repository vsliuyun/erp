<template>
  <div id="app">
    <div>  
      <top></top>
    </div>
    <div class="main_content">
      <div class="main_left">
        <sideBar></sideBar>
        <el-button type="primary" icon="arrow-left">上一页</el-button>
      </div>
      <div class="main_right"><router-view></router-view></div>
    </div>
   
  </div>
</template>


<script type="text/javascript">

import top from './components/header.vue'
import sideBar from './components/sideBar.vue'

export default {
  name: 'app',
  components:{
    top,
    sideBar
  }
}
</script>

<style type="text/css">
#app {
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow: hidden;
}
#app .main_content{
  display: flex;
}
#app .main_left{
 
}
#app .main_right{
    flex: 1;
}
</style>
