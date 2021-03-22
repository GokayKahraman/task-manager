<template>
  <div class="deneme">
    <div>
      <input
        type="checkbox"
        id="mycheck"
        name="kontrol"
        value="kontrol"
        v-model="check"
      />
    </div>

    <div v-if="check">
      <p v-for="item in forArray" :key="item" >{{ item.isim }} {{ item.soyisim }}</p>
    </div>

  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      check: false,
      forArray: [
          {
          isim: "haluk",
          soyisim: "keskin"
        },
          {
          isim: "gökay",
          soyisim: "kahraman"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
.kimlik {
  margin-top: 30px;
}

.text {
  float: left;
  margin-left: 4px;
}
</style>
