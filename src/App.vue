<template>
<div>
  <div class="text">

    <div class="style" style="margin-top: 168px;">Hi there! Welcome to</div>
      <img src="./assets/image.png" style="margin-top: 24px;"/>
      <div class="style" style="margin-top: 94px;">Very simple Things To-Do List. Helps you to<br>manage yourdaily life, without any hassle!</div>
    </div>

    <div class="footer">
      <a href="https://www.instagram.com/gokykh_/">
        <div class="link facebook">
                
          <div class="logo darkblue"></div>
          <div class="linkintext">FACEBOOK</div>                
        </div>
      </a>
        
      <a href="https://twitter.com/GokayKh">
        <div class="link twitter" style="margin-top: 15px;">
               
          <div class="logo blue"></div>
          <div class="linkintext">TWITTER</div>
                
        </div>
      </a>
    </div>   
</div>
</template>

<script>

</script>

<style lang="scss" scoped>
 @font-face {
    font-family: "Raleway";
    src: url("./assets/Raleway-Regular.ttf");
}

.text {
    text-align: center;
}

.style {
    font-family: Raleway;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;

    color: #050505;

}

.footer {
    margin-top: 145px;
    margin-left: 48px;
}

.link {
    display: flex;

    width: 280px;
    height: 50px;
    border-radius: 3px;
    color: white;
}

.logo {
    width: 50px;
    height: 50px;
    border-radius: 3px;
}

.darkblue {
    background-color: #283B68;
    background-image: url("./assets/face.png");
    background-repeat:no-repeat;
    background-position:center;
}

.blue {
    background-color: #51B2E0;
    background-image: url("./assets/twit.png");
    background-repeat:no-repeat;
    background-position:center;
}
.linkintext {
    margin-left: 23px;
    margin-top: 19px;

    font-family: Raleway;
    font-style: normal;
    font-weight: bold;
    font-size: 11px;
    line-height: 13px;


    letter-spacing: 1px;

    color: #FFFFFF;
}

.facebook {
    background-color: #3B5798;
}

.twitter {
    background-color: #59DCFF;
}
</style>
