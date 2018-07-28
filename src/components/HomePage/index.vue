<template lang="html">
  <div>
    <div class="header">
      <div class="header-container">
        <div class="">
          <img class="img-word" src="~@/assets/good.png" alt="">
        </div>
        <div class="">
          <img class="img-word" src="~@/assets/ideas.png" alt="">
        </div>
        <div class="header-title">
          想掛號嗎
        </div>
      </div>
    </div>
    <div class="register-board">
      <div class="register-board-title">
        掛號列表
      </div>
      <div class="register-lists">
        <div class="list">
          <div class="list-image">
            <img src="http://m1.ablwang.com/uploadfile/2017/0901/20170901042508280.jpg" alt="">
          </div>
          <div class="list-info">
            <div class="info-block">
              <div class="info-title">
                切版
              </div>
              <div class="info-date">
                5/23
              </div>
              <div class="info-name">
                kai
              </div>
            </div>
            <div class="info-content">
              切完第七個版
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name:'HomePage',
  data(){
    return{

    }
  },
  mounted(){

  }
}
</script>

<style lang="scss" scoped>
  .header{
    background-image: url('~@/assets/header.png');
    background-size: cover;
    background-position: center;

    .header-container{
      width: 50%;
      margin: 0 auto;
      padding: 0 5em;
      text-align: center;
      background-color: rgba(87, 81, 81,0.4);

      .img-word{
        width: 100%;
      }

      .header-title{
        color: #fff;
        font-size: 3em;
        padding: 0.3em 0;
        font-weight: 600;
      }
    }
  }
  .register-board{
    width: 70%;
    margin: 0 auto;
    margin-top: 3em;
    .register-board-title{
      color:#0f375b;
      font-size: 2em;
      margin-bottom: 0.7em;
    }
    .register-lists{
      .list{
        display: flex;
        .list-image{
          width: 20%;
          img{
            width: 100%;
            border-radius: 50%;
          }
        }
        .list-info{
          display: flex;
          width: 80%;
          background-color: rgba(30,139,166,.1);
          .info-block{
            padding-left: 1em;
            padding-top: 1em;
            width: 30%;
            .info-title{
              color: #7a062e;
              font-size: 20px;
            }
            .info-date{
              color: #1e8ba6;
              font-size: 18px;
            }
            .info-name{
              color: #0f375b;
              font-size: 20px;
            }
          }
          .info-content{
            padding-left: 1em;
            padding-top: 1em;
            width: 70%;
          }
        }
      }
    }
  }
</style>
