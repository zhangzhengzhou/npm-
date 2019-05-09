<template>
  <ul>
    <!--<li v-for="(item, index) in items" :key="index">{{item}}</li>-->
   <li>我是子组件 哈333哈哈</li>
  </ul>

</template>
<style>
  ul li {
    background: pink;
    font-size: 140px;
    color:red;
  }
</style>
<script>
//  import SeamlessScroll from 'seamless-scroll';

  export default {
    name: 'Zhang',
    props: {
      items: Array
    },
    mounted() {
//      var scroller = new SeamlessScroll({
//        el: 'box',
//        direction: 'left',
//        width: 375,
//        height: 175,
//        autoPlay: true
//      });

// 用户点击“开始按钮”时，调用实例的 start 方法，开始播放
//      const startBtn = document.getElementById('start-btn');
//      startBtn.addEventListener('click', function() {
//        scroller.start();
//      });
    }
  }
</script>

<style scoped>
  /*ul{*/
    /*background-color: pink;*/
  /*}*/
  /*ul li{*/
    /*list-style: decimal;*/
  /*}*/
</style>
