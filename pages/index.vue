<template>
  <div class="container">
    <div class="space" />
    <div class="car-red" />

    <span class="title">
      Drive your sTSLA to the Moon
    </span>

    <p class="paragraph">
      Exchange your boring USDC for a token that's going places: Synthetic TSLA.  Hurry, your ride is leaving soon!
    </p>

    <div
      class="button"
      @click="$router.push({ path: '/modal' })"
    />

    <span class="button-text">Get sTSLA</span>

    <div class="car-gray" />
    <a class="github-icon" href="https://github.com/tsla-exchange" target="_blank" />
    <a class="twitter-icon" href="https://twitter.com/ItsNickBarry" target="_blank" />
    <a class="network-icon" href="https://kwenta.io/" target="_blank" />
  </div>
</template>

<style>
/* .__nuxt and .__layout */
html, body, body > div, body > div > div {
  height: 100%;
}

* {
  overflow-x: hidden;
  padding: 0px !important;
  margin: 0px !important;
}
.container {
  width: 100%;
  height: 100%;
  min-height: 950px;
  background: linear-gradient(rgba(0,2,75,1), rgba(39,30,110,1));
  opacity: 1;
  position: relative;
  top: 0px;
  left: 0px;
  overflow: hidden;
}
.space {
  width: 100%;
  height: 100%;
  background: url("../static/space.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  bottom: 0px;
  right: 0px;
  overflow: hidden;
}
.car-red {
  width: 200px;
  height: 100px;
  background: url("../static/car-red.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 580px;
  left: 175px;
  transform: rotate(-32deg);
  overflow: hidden;
}
.title {
  width: 470px;
  color: rgba(255,255,255,1);
  position: absolute;
  top: 134px;
  left: 70px;
  font-family: Roboto Condensed;
  font-weight: bold;
  font-size: 64px;
  opacity: 1;
  text-align: left;
}
.button {
  width: 186px;
  height: 48px;
  background: linear-gradient(rgba(130,68,176,1), rgba(255,0,119,1));
  opacity: 1;
  position: absolute;
  top: 490px;
  left: 70px;
  border-top-left-radius: 50px;
  border-top-right-radius: 50px;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 50px;
  overflow: hidden;
  cursor: pointer;
}
.button:hover {
  background: linear-gradient(rgba(107,57,145,1), rgba(209,0,97,1));
}
.button-text {
  width: 125px;
  color: rgba(255,255,255,1);
  position: absolute;
  top: 500px;
  left: 113px;
  font-family: Montserrat;
  font-weight: bold;
  font-size: 20px;
  opacity: 1;
  text-align: left;
  pointer-events: none;
}
.paragraph {
  width: 500px;
  color: rgba(147,159,189,1);
  position: absolute;
  top: 325px;
  left: 70px;
  font-family: Montserrat;
  font-weight: normal;
  font-size: 24px;
  opacity: 1;
  text-align: left;
}
.car-gray {
  width: 400px;
  height: 225px;
  background: url("../static/car-gray.png");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 750px;
  left: 300px;
  overflow: hidden;
}
.github-icon {
  width: 35px;
  height: 35px;
  background: url("../static/github_1.png");
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 750px;
  left: 70px;
}
.twitter-icon {
  width: 35px;
  height: 35px;
  background: url("../static/twitter.png");
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 815px;
  left: 70px;
}
.network-icon {
  width: 35px;
  height: 35px;
  background: url("../static/share.png");
  background-size: cover;
  opacity: 1;
  position: absolute;
  top: 880px;
  left: 70px;
}
</style>
