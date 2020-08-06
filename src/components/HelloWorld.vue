<template>
  <div>

    <div>
      <img id="topbg" src="../assets/top_bg.png">
      <div id="topleft">
        <img id="icon" src="../assets/icon.png">

        <div class="kaixin">
          <div id="kaixin_red_line"/>
          <div id="kaixin_title">开心0元购</div>
        </div>
        <font class="noti">连续打卡全额返 就在开心0元购</font>
        <div class="btnP" @click="openNewTab()">
          <img class="btnImg" src="../assets/bot.png">
          <font class="btnFont">Android下载</font>
        </div>
      </div>

      <img id="shouji" src="../assets/shouji.png">
    </div>

    <div >
      <div class="bottom1">
        <div class="WordP">
          <h1>打卡简单 全额返购自主提现</h1>
          <h2>只要坚持完成连续打卡任务 即全额返现</h2>
          <h3>• 进入指定京东或天猫店铺购买想要的指定商品</h3>
          <h3>• 进入开心0元购注册账号，关联商品</h3>
          <h3>• 每日打卡，完成阶段任务自主提现，直至全额</h3>
        </div>
        <img class="img1" src="../assets/right_top.png">
      </div>

      <div class="bottom2">
        <img class="img2" src="../assets/left_bottom.png">
        <div class="WordP">
          <h1>提现便捷 拒绝意外翻车</h1>
          <h2>分阶段返现，完成阶段任务即可直接提现</h2>
          <h3>• 在开心0元购打卡至阶段任务完成</h3>
          <h3>• 进入领奖处，填写收款账户直接申请提现</h3>
          <h3>• 全部现金到账，更有神秘福利免费领取</h3>
        </div>
      </div>

    </div>

  </div>
</template>

<!--(1920 px 1082 px)-->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  #topbg {
    width: 100%;
    height: 100%;
  }

  #topleft {
    left: 213px;
    top: 224px;
    position: absolute;
    text-align: left;
  }

  #icon {
    width: 144px;
    height: 144px;
  }

  .kaixin {
    position: relative;
    display: table;
  }

  #kaixin_red_line {
    height: 20px;
    width: 100%;
    background-color: #FB4645;
    position: absolute;
    bottom: 0;
    opacity: 0.9;
  }

  #kaixin_title {
    color: black;
    font-size: 40px;
    font-weight: bold;
  }

  .noti {
    margin-top: 20px;
    color: #FB4644;
    font-weight: bold;
    font-size: 20px;
    position: absolute;
    white-space:nowrap;
  }

  .btnP {
    width: 300px;
    height: 66px;
    position: relative;
    margin-top: 70px;
    border-radius: 33px;
    background-color: #FB4644;
  }

  .btnImg {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    margin-left: 40px;
  }

  .btnFont {
    color: white;
    font-size: 28px;
    font-weight: bold;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    right: 40px;
    /*left: auto;*/
  }

  #shouji {
    width: 400px;
    height: 380px;
    right: 213px;
    top: 224px;
    position: absolute;
  }

  .bottom1{
    display: inline-flex;
    margin-top: 50px;
  }

  .WordP{
    text-align: left;
  }
  .WordP h1{
    font-size: 30px;
  }
  .WordP h2{
    font-size: 20px;
  }
  .WordP h3{
    font-size: 14px;
  }
  .img1{
    margin-left: 200px;
    width: 400px;
    height: 300px;
  }
  .bottom2{
    display: inline-flex;
    margin-top: 50px;
  }
  .img2{
    margin-right: 200px;
    width: 400px;
    height: 300px;
  }
</style>

<script>
  import bg from '../assets/top_bg.png';

  export default {
    name: 'lingyuangou',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App',
      }
    },
    methods: {
      openNewTab() {
        window.open("http://d.firim.info/freepa", "_blank");
      },
    }
  }
</script>

<!--本地网络地址：   http://192.168.31.101:8082-->
