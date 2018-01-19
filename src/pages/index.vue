<template>
  <div>
      
      <!-- 底部tabbar start-->
      <tabbar>
          <tabbar-item>
              <img slot="icon" src="@/assets/logo.png">
              <span slot="label">首页</span>
          </tabbar-item>
           <tabbar-item>
              <img slot="icon" src="@/assets/logo.png">
              <span slot="label">分类</span>
          </tabbar-item>
          <tabbar-item>
              <img slot="icon" src="@/assets/logo.png">
              <span slot="label">收藏</span>
          </tabbar-item>
      </tabbar>
      <!-- 底部tabbar end-->
  </div>
</template>




<script>
import {Tabbar,TabbarItem} from 'vux'
export default {
    components:{
        Tabbar,
        TabbarItem
    }
  
}
</script>

