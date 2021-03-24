<template>
  <div class="main">
    <div style="margin-top: 168px;">Hi there! Welcome to</div>
    <img src="./assets/image.png" style="margin-top: 24px;" />
    <div style="margin-top: 94px;">
      Very simple Things To-Do List. Helps you to<br />manage yourdaily life,
      without any hassle!
    </div>

    <div class="footer">
      <div class="social-container facebook">
        <a class="social-link" href="https://www.instagram.com/gokykh_/">
          <div class="facebook-logo"></div>
          <div class="social-title">FACEBOOK</div>
        </a>
      </div>

      <div class="social-container twitter" style="margin-top: 15px;">
        <a class="social-link" href="https://twitter.com/GokayKh">
          <div class="twitter-logo"></div>
          <div class="social-title">TWITTER</div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
//js
</script>

<style lang="scss" scoped>
@font-face {
  font-family: "Raleway";
  src: url("./assets/Raleway-Regular.ttf");
}
.main {
  text-align: center;
  font-family: Raleway;
  font-style: normal;

  font-weight: normal;
  font-size: 14px;

  color: #050505;
}

.text {
  text-align: center;
}

.footer {
  margin-top: 145px;
}

.social-container {
  width: 280px;
  height: 50px;
  border-radius: 3px;
  color: white;
  margin: auto;
}

.facebook-logo {
  width: 50px;
  height: 50px;
  border-radius: 3px;

  background-color: #283b68;
  background-image: url("./assets/face.png");
  background-repeat: no-repeat;
  background-position: center;
}

.twitter-logo {
  width: 50px;
  height: 50px;
  border-radius: 3px;

  background-color: #51b2e0;
  background-image: url("./assets/twit.png");
  background-repeat: no-repeat;
  background-position: center;
}

.social-title {
  margin-left: 23px;
  margin-top: 19px;

  font-family: Raleway;
  font-style: normal;
  font-weight: bold;
  font-size: 11px;
  letter-spacing: 1px;

  color: #ffffff;
}

.facebook {
  background-color: #3b5798;
}

.twitter {
  background-color: #59dcff;
}
.social-link {
  display: flex;
  text-decoration: none;
}
</style>
