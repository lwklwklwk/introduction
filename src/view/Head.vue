<template>
  <div class="half-screen head-box" >
    <div class="introduce">你好，我是可疑的团子，</div>
    <div class="small-introduce">现住于广州</div>
    <div class="introduce">一个前端工程师。</div>
    <div class="small-introduce">也懂一点后端~</div>
  </div>
</template>
<script>

export default {
  components: {
  
  },
  data(){
    return {
    }
  }
}
</script>

<style scoped>
.head-box{
  flex-direction: column
}
.introduce{
  width: 50vw;
  color: #444;
  font-size: 3vw;
}
.small-introduce{
  width: 50vw;
  color: #ccc;
  font-size:1.5vw
}
</style>
