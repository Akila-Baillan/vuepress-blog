<template>
  <div class="home-main-page">
    <div class="cardpage" style="padding-bottom: 88px;">
      <el-card shadow="always" :body-style="{ padding: '0px' }" class="box-card">
        <img
          src="/church_s.png"
          class="image"
        >
        <div class="nickname">
          <span class="nick">P & L</span>
        </div>
        <div style="padding: 16px;" class="motto">
          <span>The wedding will take place on January 19, 2020.</span>
        </div>
      </el-card>
    </div>

    <hr>
    <div class="footer">
      <p>我有一轮月，能跨山海隔。</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {
    // openPage(url) {
    //   window.open(url);
    // }
  }
};
</script>

<style scoped>
@media (min-width: 1200px) {
  .cardpage {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    overflow-x: hidden;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    margin-top: 120px;
  }
  .nickname span {
    font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
      "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
    font-weight: 700;
    font-size: 22px;
    color: #e89224;
  }
  .motto span {
    font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
      "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
    font-weight: 700;
    font-size: 16px;
    color: cadetblue;
  }

  .image {
    margin-top: 20px;
    margin-bottom: 30px;
    /* width: 250px; */
    height: 260px;
    border-radius: 5px;
  }
  .box-card {
    width: 500px;
  }
  .footer {
    height: 5%;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #e89224;
    font-size: 14px;
  }
}

@media (max-width: 1200px) {
  .box-card {
    width: 100%;
  }
  .cardpage {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 300px;
    overflow-x: hidden;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    margin-top: 60px;
  }
  .nickname span {
    font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
      "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
    font-weight: 700;
    font-size: 22px;
  }
  .motto span {
    font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
      "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
    font-weight: 700;
    font-size: 16px;
    color: cadetblue;
  }
  .image {
    margin-top: 20px;
    margin-bottom: 20px;
    width: 100px;
    height: 100px;
    border-radius: 50%;
  }
  .footer {
    height: 5%;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
  }
}
</style>
<style>
.cardpage>.el-card >.el-card__body {
  display: flex; flex-direction: column; align-items: center; justify-content: center;
}
</style>
