<template>
  <div class="home-Sponsor">
    <div class="home-Sponsor_Wave"></div>
    <div class="st-Container">
      <h2 class="home-Sponsor_Title">SPONSOR</h2>
      <p class="home-Sponsor_Description">初心者から上級者まで楽しめるセッションが目白押し！これから始めようと思っていたフレームワークや、気になっていた技術についての情報が得られるかも！？</p>
      <div class="home-Sponsor_Sponsor">
        <div class="home-Sponsor_Platinum">
          <h3>プラチナスポンサー</h3>
          <div class="home-Sponsor_Large"></div>
          <div class="home-Sponsor_Large"></div>
        </div>
        <div class="home-Sponsor_Gold">
          <h3>ゴールドスポンサー</h3>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
          <div class="home-Sponsor_Medium"></div>
        </div>
        <div class="home-Sponsor_Silver">
          <h3>シルバースポンサー</h3>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
          <div class="home-Sponsor_Small"></div>
        </div>
        <div class="home-Sponsor_Media">
          <h3>メディアスポンサー</h3>
          <div class="home-Sponsor_Small"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  @import "~assets/scss/library/_variable.scss";
  @import "~assets/scss/library/_mixin.scss";

  .home-Sponsor {
    padding: 70px 0 70px 0;
    width: auto;
    background: $clr_baseDark;

    &_Wave {
      width: 100%;
      height: 20px;
      background-image: url("/images/wavyLine-dark.png");
      background-repeat: repeat-x;
      background-size: contain;
      position: relative;
      top: -90px;
    }

    &_Title {
      @include secTitle;
    }

    &_Description {
      max-width: 770px;
      width: 100%;
      margin: 0 auto;
      padding: 0 0 30px 0;
    }

    &_Large {
      display: inline-block;
      max-width: 330px;
      width: 100%;
      height: 230px;
      background: $clr_baseWhite;
      margin: 0 5px 30px 5px;

      @include desktop() {
        max-width: 440px;
        height: 260px;
        margin: 0 15px 40px 15px;
      }
    }

    &_Medium {
      display: inline-block;
      max-width: 150px;
      width: 100%;
      height: 110px;
      background: $clr_baseWhite;
      margin: 0 5px 5px 5px;

      @include desktop() {
        max-width: 215px;
        height: 140px;
        margin: 0 10px 10px 10px;
      }
    }

    &_Small {
      display: inline-block;
      max-width: 100px;
      width: 100%;
      height: 75px;
      background: $clr_baseWhite;
      margin: 0 5px 5px 5px;

      @include desktop() {
        max-width: 150px;
        height: 120px;
        margin: 0 10px 10px 10px;
      }
    }
  }
</style>
