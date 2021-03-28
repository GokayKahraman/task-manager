<template>
  <div id="app">

    <div class="header">
      <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
      <div class="container">

        <a class="header-logo" href="">
          <img src="./assets/booklogo.png" alt="">
        </a>

        <button class="header-switch" type="button">
          <svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32">
          <title>icon-menu</title>
          <path d="M2 6h28v6h-28zM2 14h28v6h-28zM2 22h28v6h-28z"></path>
          </svg>
        </button>

        <div class="header-menu">

          <div class="header-menu-user">
            <a href="">Register</a>
            <a href="">Sing In</a>
          </div>

          <a class="header-menu-property button" href="">List your property</a>

          <div class="header-menu-helper">
            <select>
              <option value="en">en</option>
            </select>
            <select>
              <option value="en">UAH</option>
            </select>
          </div>
        </div>
      </div>
    </div>

    <nav class="navigation">
      <div class="contain">
        <a class="navigation-item" href="">Menü1</a>
        <a class="navigation-item" href="">Menü2</a>
        <a class="navigation-item" href="">Menü3</a>
        <a class="navigation-item" href="">Menü4</a>
      </div>

    </nav>

    <main class="main">
      <section class="showcase">
        <div class="container">
          <h1>More deals than days in a year</h1>
          <h4>From cosy country homes to funky city flats</h4>

          <div class="search">
            <form class="search-form" action="">
              <div class="search-form-item">
                <div class="form-item">
                  <svg class="icon icon-pin_drop" version="1.1" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32">
                    <title>location</title>
                    <path d="M16 0c-5.523 0-10 4.477-10 10 0 10 10 22 10 22s10-12 10-22c0-5.523-4.477-10-10-10zM16 16c-3.314 0-6-2.686-6-6s2.686-6 6-6 6 2.686 6 6-2.686 6-6 6z"></path>
                  </svg>
                  <input class="text" type="text" placeholder="Location">
                </div>
                <p class="form-description">Destination,property name or address</p>
              </div>
              <div class="search-form-item">
                <div class="form-item">
                  <svg class="icon icon-date_range" version="1.1" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32">
                    <title>calendar</title>
                    <path d="M10 12h4v4h-4zM16 12h4v4h-4zM22 12h4v4h-4zM4 24h4v4h-4zM10 24h4v4h-4zM16 24h4v4h-4zM10 18h4v4h-4zM16 18h4v4h-4zM22 18h4v4h-4zM4 18h4v4h-4zM26 0v2h-4v-2h-14v2h-4v-2h-4v32h30v-32h-4zM28 30h-26v-22h26v22z"></path>
                  </svg>
                  <input class="text" type="date">
                </div>
                <p class="form-description">when</p>
              </div>
              <div class="search-form-item">
                <div class="form-item">
                  <svg class="icon icon-user_range" version="1.1" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32">
                    <title>user</title>
                    <path d="M18 22.082v-1.649c2.203-1.241 4-4.337 4-7.432 0-4.971 0-9-6-9s-6 4.029-6 9c0 3.096 1.797 6.191 4 7.432v1.649c-6.784 0.555-12 3.888-12 7.918h28c0-4.030-5.216-7.364-12-7.918z"></path>
                  </svg>
                  <select class="select">
                    <option value="">123</option>
                  </select>
                </div>
                <div class="search-form-item">
                  <button type="button" class="button button-full">Let's get started</button>
                  <div class="for-work">
                    <label class="form-checkbox">
                      are you travelling for work?
                      <div class="checkbox">
                        
                        <input type="checkbox">
                      </div>
                    </label>
                  </div>
                </div>
              </div>

              
            </form>
            
          </div>

          <ul class="showcase-shortlink">
            <a href="">Find deals</a>
            <a href="">Travel guides</a>
            <a href="">how was your stay</a>
            <a href="">holiday rentals</a>
            <a href="">for business</a>
          </ul>
        </div>
      </section>
    </main>
    
  </div> 
</template>

<script>

</script>

<style lang="scss" scoped>
$max-width: 1140px;
$gutter: 20px;
$border-radius: 3px;
$finger-size: 44px;
//
$color-navy: #083B87;
$color-blue: #01ACEE;
$color-softblue: #F1F6FF;
$color-yellow: #FBBE00;
//
$font-family: 'Open Sans', Arial, sans-serif;
$font-size: 16px;
$font-size-small: .9em;

@mixin mq($width: "tablet"){
  @if($width == "tablet") {
    @media (min-width: 768px) { 
      @content
    }
  }; 
  @if($width == "desktop") {
    @media (min-width: 992px) {
      @content 
    }
  };
  @if($width == "large") {
    @media (min-width: 1200px) {
      @content
    }
  }  
}

.header {
  max-width: $max-width;
  margin: auto;
  height: 68px;

  .container{
    position: relative;
    display:flex;
    align-items: center;
    height: 68px;
    margin-left: auto;
    margin-right: auto;
    padding-left: $gutter;
    padding-right: $gutter;
  }
  &-switch {
    margin-left: auto;
    @include mq {
      display: none;
    }
    
    background-color: transparent; 
    border: none;
  }

  &-menu{
    display: flex;
    position: fixed;
    left: 0px;
    right: 0px;
    top: 100%;
    padding-left: $gutter;
    padding-right: $gutter;
    padding-bottom: 20px;
    flex-direction: column;
    background-color: white;
    box-shadow: 0 20px 30px rgba(black, .2);

    @include mq("tablet") {
      display: flex;
      margin-left: auto;
      flex-direction: row;
      position: static;
      box-shadow: none;
      background-color: transparent;
      padding-left: 0px;
      padding-right: 0px;
      padding-bottom: 0px;
    }


    &-user {
      margin-right: 10px;
      display: flex;
      flex-direction: column;
      align-items: center;
      @include mq("tablet") {
        flex-direction: row;
      }

      a {
        width: 100%;
        justify-content: center;
        text-decoration: none;
        display: inline-flex;
        align-items: center;
        padding-left: 20px;
        padding-right: 20px;
        height: $finger-size;
        &:hover {
          background-color: #eee;
          }
        }
    }

    &-property {
      margin-top: 20px;
      justify-content: center;
      @include mq("tablet") {
        margin-top: 0px;
      }
    }


    &-helper {
      margin-top: 20px;
      display: flex;
      justify-content: center;

      @include mq("tablet") {
        margin-left: 20px;
        margin-top: 0px;
      }

      select {
        appearance: none;
        background-color: transparent;
        border: 1px solid $color-softblue;
        padding-left: 10px;
        padding-right: 10px;
        border-radius: 0;
        color: $color-navy;
      }

      &:nth-child(1) {
        border-bottom-left-radius: $border-radius;
        border-top-left-radius: $border-radius;
      }
      &:nth-child(2) {
        border-left-width: 0;
        border-bottom-right-radius: $border-radius;
        border-top-right-radius: $border-radius;
      }
    }

  }
  &-logo {
    img {
      width: 144px;
    }
  }

}

.container{
  max-width: $max-width;
  margin-left: auto;
  margin-right: auto;
  padding-left: $gutter;
  padding-right: $gutter;
  text-align: center;
}

.button {
  text-decoration: none;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  padding-left: 20px;
  padding-right: 20px;
  height: $finger-size;
  background-color: $color-blue;
  color: white;
  border-radius: $border-radius;
  font-weight: bold;
  font-family: inherit;
  border: 0px;
  text-align: center;

  &-full {
    margin-top: 50px;
    width: 100%;
  }
}

.navigation {
  height: 68px;
  background-color: $color-softblue;

  .contain {
    height:100%;
    display: flex;
    align-items: center;
  }
  &-item {
    margin-right: 20px;
    margin-left: 40px;
    font-size: .90em;
    color: $color-navy;
    
  }

}

.showcase {
  padding-top: 30px;
  padding-bottom: 30px;
  background-color: $color-navy;
  
  color:white;
  
  &-shortlink {
    margin-top: 60px;
    display: flex;
    align-items: center;
    justify-content: center;

    a {
      margin-left: 10px;
      margin-right: 10px;
      color: white;
      text-decoration: none;

      &:hover {
        text-decoration: underline;
      }
    }
  }
}

.search {
  text-align: left;
  margin-top: 30px;
  background-color: orange;
  padding: $gutter;
  box-shadow: 0 20px 40px rgba(black, .2);

  @include mq("tablet") {
    padding: 50px;
    margin-top: 50px;
    margin-left: 100px;
    margin-right: 100px;
  }

  &-form {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: flex-start;

    @include mq("tablet") {
      flex-direction: row;
    }

    &-item {
      width: 100%;
      @include mq("tablet") {

      }
      & + & {
        margin-top: 20px;
        @include mq("tablet") {
          flex-grow: 1;
          margin-top: 0;
          margin-left: 10px;
        }
      }
    }
  }

  .for-work {
    font-size: $font-size-small;
    margin-bottom: 10px;
    display: flex;
    justify-content: center;

    @include mq("tablet") {
      position: absolute;
      top: calc(#{$finger-size} + 20px);
      right: 0;
    }

    .checkbox {
      margin-left: 10px;
    }
  }

}

.text {
  font-family: inherit;
  border: 0px;
  min-height: $finger-size;
  border-radius: $border-radius;
  color: $color-navy;
  font-weight: bold;
  padding-left: 10px;
  padding-right: 10px;
  width: 100%;
}

.select {
  border: 0px;
  background-color: white;
  font-family: inherit;
  display: inline-block;
  width: 90%;
  height: $finger-size;
  border-radius: $border-radius;
  font-weight: bold;
}

.form-item {
  position: relative;
  display: flex;
  margin-right: 5px;

  .icon {
    height: 28px;
    position: absolute;
    left:0px;
    top: 50%;
    transform: translateY(-50%);
   
  }

  .text {
    padding-left: 40px;
  }

  .select {
    padding-left: 40px;
    width: 120%;

  }
}
.form-description {
  margin-top: 20px;
  font-size: 14px;
}
.form-checkbox {
  display: flex;
}


</style>
