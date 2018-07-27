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
</style>
