<template>
   <div id="sideBar"> 
        <el-button type="primary" icon="edit"></el-button>
<el-button type="primary" icon="share"></el-button>
<el-button type="primary" icon="delete"></el-button>
<el-button type="primary" icon="search">搜索</el-button>
<el-button type="primary">上传<i class="el-icon-upload el-icon--right"></i></el-button>
   </div> 
</template>


<script type="text/javascript">

  import '../sass/sideBar.scss'

    export default {
        name: 'sideBar',
        data () {
            return {
            
            }
        }
    }
</script>