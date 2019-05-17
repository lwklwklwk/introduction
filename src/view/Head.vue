<template>
  <div class="half-screen">
    <h1>可疑的团子</h1> 
    <div class="center-box">
      <div class="head-info">
        <img class="head-pic"  src="../assets/logo.png" >
        <lwk-list :mainInfo="mainInfo"></lwk-list>        
      </div>

    </div>
  </div>
</template>
<script>
import lwkList from '../components/lwkList.vue'
export default {
  components: {
    lwkList
  },
  data(){
    return {
      mainInfo:[{label:"姓名",value:"lwk"},{label:"电话",value:"15602341972"},{label:"邮箱",value:"scau_lwk@163.com"}]
    }
  }
}
</script>

<style scoped>

.center-box{
  display: flex;
  flex-direction: column;
  /* border: 1px solid ; */
  padding: 2vh;
  box-sizing: border-box;
}@media screen and (min-width: 0px) and (max-width: 900px){

}
.head-pic{
  height: 100%;
  width: 30%;
  margin-right:5%; 
  border: 1px solid;
}
.head-info{
  display: flex;
}
</style>
