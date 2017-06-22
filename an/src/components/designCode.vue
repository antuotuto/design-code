<template>
  <div class="designCode">
    <header>
      <div class="versions">
        <p>2.0</p>
      </div>
      <p class="header-text">WEB端残联系统视觉设计规范</p>
    </header>
    <main>
      <div class="box-out">
        <div class="font box">
          <i class="icon iconfont icon-font"></i>
          <p>字体设计规范</p>
        </div>
        <div class="icon box">
          <i class="icon iconfont icon-tupian"></i>
          <p>图片使用规范</p>
        </div>
        <div class="photo box">
          <i class="icon iconfont icon-check"></i>
          <p>正确的设计</p>
        </div>
        <div class="component box">
          <i class="icon iconfont icon-app"></i>
          <p>组件使用规范</p>
        </div>
      </div>
    </main>

    <footer>
    <div class="font-design">
      <div class="design-box">
        <p class="big">颜色设计及使用规范</p>
        <p class="small">基础使用规范汇集</p>
      </div>
    </div>
    <div class="center">
      <div class="font-design-content">
        <p class="number"><span>1 </span> 正常模式颜色使用</p>
      </div>
    </div>

    </footer>



  </div>
</template>

<script>

export default {
  name: 'designCode',
  data () {
    return {

    }
  },
  components: {
  }
}
</script>

<style scoped lang="scss">
$background: #03a67b;
$color: #eee;
.designCode{
  height:100%;
  width:100%;
  header{
    height:500px;
    background: $background;
    padding-top: 100px;
    color:#fff;
    .versions{
      height:200px;
      width:200px;
      margin: 0 auto;
      border: 1px solid #fff;
      border-radius: 200px;
      p{
        line-height: 200px;
        text-align: center;
        font-size: 100px;
        font-weight: 100;
        margin: 0;
      }
    }
    .header-text{
      text-align: center;
      padding-top: 50px;
      font-size: 30px;
      letter-spacing: 1px;
      font-weight: 200;
    }
  }
  main{
    height:400px;
    background: #F8F6F7;
    padding-top: 150px;
    .box-out{
      width:900px;
      margin: 0 auto;
    }
    .box{
      height:100px;
      width:100px;
      background: $background;
      border-radius: 100px;
      float: left;
      margin-left: 100px;
      text-align: center;
      i{
        color:#fff;
        font-size: 35px;
        line-height: 100px;
      }
      p{
        font-size: 15px;
        padding-top: 5px;
        color:#676767;
      }
    }
  }
  footer{
    padding-bottom: 500px;
    background: #F8F6F7;
    .center{
      width:900px;
      margin: 0 auto;
    }
    .font-design{
      height:200px;
      background: $background;
      padding-top: 60px;
      .design-box{
        width:400px;
        margin: 0 auto;
        color:#fff;
        .big{
          font-size: 40px;
          font-weight: 200;
          margin-bottom: 0;
        }
        .small{
          font-size: 12px;
          font-weight: bold;
          text-align: right;
          padding-right: 42px;
        }
      }
    }
    .font-design-content{
      padding-top: 100px;
      .number{
        height:40px;
        line-height: 40px;
        font-size: 17px;
        color: #058563;
        span{
          height:40px;
          width:40px;
          font-size: 20px;
          color:#fff;
          margin-right: 10px;
          display: inline-block;
          border-radius: 30px;
          text-align: center;
          background: $background;
        }
      }
    }


  }
}
</style>
