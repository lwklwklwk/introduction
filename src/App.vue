<template>
  <div>
    <Head></Head>
    <Main></Main>
  </div>
</template>

<script>
import Head from './view/Head.vue'
import Main from './view/Main.vue'
export default {
  name: 'app',
  components: {
    Head,
    Main
  }
}
</script>

<style>
*{
  margin:0;
  padding:0;
  /* font-size: 20px  */
}
/* @media screen and (min-width: 0px) and (max-width: 500px){
  *{
    font-size: 14px;
  }
} */
.half-screen{
  margin: 2vh 2vw 0 2vw;
  height: 50vh;
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.children-center{
    display:flex;
    justify-content:center;
    align-items: center;
}
</style>
