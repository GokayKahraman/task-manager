<template>
  <div>
    <div class="header">
      <div class="container">

        <a class="header-logo" href="">
          <img src="./assets/booklogo.png" alt="">
        </a>
        <div class="header-menu">

          <div class="header-menu-user">
            <a href="">Register</a>
            <a href="">Sing In</a>
          </div>

          <a class="button" href="">List your property</a>

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


  </div> 
</template>

<script>

</script>

<style lang="scss" scoped>
$gutter: 20px;
$max-width: 1500px;
$color-navy: #083B87;
$color-blue: #01ACEE;
$color-softblue: #F1F6FF;
$finger-size: 36px;
$border-radius: 2px;

.header {
  max-width: $max-width;
  margin: auto;

  .container{
    display:flex;
    align-items: center;
    height: 64px;
    margin-left: auto;
    margin-right: auto;
  }

  &-menu{
    margin-left: auto;
    display: flex;

    &-user {
      display: flex;
      a {
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
    &-helper {
      display: flex;
      margin-left: 20px;

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
  background-color: white;
}

.button {
  text-decoration: none;
  display: inline-flex;
  align-items: center;
  padding-left: 20px;
  padding-right: 20px;
  height: $finger-size;
  background-color: $color-blue;
  color: white;
  border-radius: $border-radius;
  font-weight: bold;
}




</style>
