<template>
  <div>
    <div class="header">
      <div class="container">

        <a class="header-logo" href="">
          <img src="./assets/img/booklogo.png" alt="">
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
        <div class="showcase-store">
          <a href="" class="showcase-store-link">
            <img src="./assets/img/apple.svg">
          </a>
          <a href="" class="showcase-store-link">
            <img src="./assets/img/google.svg">
          </a>
        </div>
      </section>
      <section class="highlights">
        <div class="container">
          <div class="highlights-slider">
            <div class="highlights-item">
              <h4>123123</h4>
              <p>Gökay kahraman</p>
            </div>
            <div class="highlights-item">
              <h4>123123</h4>
              <p>Gökay kahraman</p>
            </div>
            <div class="highlights-item">
              <h4>123123</h4>
              <p>Gökay kahraman</p>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div> 
</template>

<script>

</script>

<style lang="scss" scoped>
  @import "assets/css/main.scss";
</style>
