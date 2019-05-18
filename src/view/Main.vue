<template>
  <div>
    <div class="half-screen" style="  background-color: #ece9e9;">
      <div class="children-center main-text-box">
        <p class="main-big-font">*关于专业技能</p>
        <p class="main-small-font" style="color:#9e9d99">熟悉常用的HTML,CSS,JS语法</p>
        <p class="main-small-font" style="color:#9e9d99">常用开发框架为VUE</p>
      </div>
      <div class="main-pic-box" style="width:50%;height:100%">
        <img src="../assets/html.png" class="img-icon" alt>
        <img src="../assets/css.png" class="img-icon" alt>
        <img src="../assets/js.png" class="img-icon" alt>
      </div>
    </div>
    <div class="half-screen" style="  background-color: #ffe324;">
      <div class="children-center main-text-box">
        <p class="main-big-font">*校园经历</p>
        <p class="main-small-font" style="color:#9d8b1e;">大学就读与华南农业大学（省建211）</p>
        <p class="main-small-font" style="color:#9d8b1e;">专业为网络工程</p>
        <p class="main-small-font" style="color:#9d8b1e;">当过班长，加入过技术工作室</p>
      </div>
      <div class="main-pic-box" style="width:50%;height:100%">
        <img src="../assets/school.png" style="width:45%" class="img-icon" alt>
      </div>
    </div>
    <div class="half-screen" style="width:46vw;float:left;  background-color:#f60c3e;">
      <div class="children-center main-text-box">
        <p class="main-big-font" style="color:#fff;">*项目经历</p>
        <p class="main-small-font" style="color:#fff">基于Vue+SpringBoot的前后端分离在线购物商场</p>
      </div>
      <div class="main-pic-box" style="width:50%;height:100%">
        <img src="../assets/shop.png" style="width:85%" class="img-icon" alt>
      </div>
    </div>
        <div class="half-screen" style="width:46vw;;  background-color:#1f1f1f;">
      <div class="children-center main-text-box">
        <p class="main-big-font" style="color:#bbb;">*项目经历</p>
        <p class="main-small-font" style="color:#666">基于Vue的管理后台前端界面</p>
      </div>
      <div class="main-pic-box" style="width:50%;height:100%">
        <img src="../assets/vue-manager.png" style="width:85%" class="img-icon" alt>
      </div>
    </div>
    <div class="half-screen" style="background-color:#987ff1;">
      <div class="children-center main-text-box">
        <p class="main-big-font" style="color:#fff;">*实习经历</p>
        <p class="main-small-font" style="color:#d0c8f0">2019.3</p>
        <p class="main-small-font" style="color:#d0c8f0">数字广东--web前端实习生</p>
      </div>
      <div class="main-pic-box" style="width:50%;height:100%">
        <img src="../assets/digitalgd.jpeg" style="width:40%" class="img-icon" alt>
      </div>
    </div>
  </div>
</template>
<script>
// import lwkList from "../components/lwkList.vue";
export default {
  components: {
    // lwkList
  },
  data() {
    return {
      mainInfo: [
        { label: "姓名", value: "lwk" },
        { label: "电话", value: "15602341972" },
        { label: "邮箱", value: "scau_lwk@163.com" }
      ]
    };
  }
};
</script>

<style scoped>
.center-box {
  display: flex;
  flex-direction: column;
  /* border: 1px solid ; */
  padding: 2vh;
  box-sizing: border-box;
}
@media screen and (min-width: 0px) and (max-width: 900px) {
}
.img-icon {
  width: 30%;
}
.main-text-box {
  margin: 0 8%;
  width: 25%;
  height: 100%;
  flex-direction: column;
}
.main-big-font {
  font-weight: 700;
  width: 100%;
  margin-bottom: 10%;
  color: #444;
  font-size: 2.5vw;
}
.main-small-font {
  width: 100%;
  color: #ccc;
  font-size: 1.25vw;
  margin-bottom: 5%;
}
.main-pic-box {
  width: 50%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.head-pic {
  height: 100%;
  width: 30%;
  margin-right: 5%;
  border: 1px solid;
}
.head-info {
  display: flex;
}
</style>
