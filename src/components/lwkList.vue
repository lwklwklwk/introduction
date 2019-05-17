<template>
  <div class="lwkList-box">
    <div style="overflow: scroll;margin-bottom:2px" v-for="item in mainInfo" :key="item.value">
      <nobr>{{item.label}}:{{item.value}}</nobr>
    </div>
    
  </div>
</template>
<script>
export default {
  props:{
    mainInfo:{}
  }
}
</script>
<style scoped>
.lwkList-box{
  width: 60%;
  
}
::-webkit-scrollbar {display:none}
*{
  -ms-overflow-style: none; 
  overflow:-moz-scrollbars-none;
} 

</style>


