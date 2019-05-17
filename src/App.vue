<template>
  <div>
    <Head></Head>
  </div>
</template>

<script>
import Head from './view/Head.vue'

export default {
  name: 'app',
  components: {
    Head
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
  height: 50vh;
  border-radius: .6rem;
  background-color: aquamarine;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
