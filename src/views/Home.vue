<template>
  <div class="deneme">
    <div>
      <input type="text" value="isim" placeholder="isim" v-model="isim" />
    </div>

    <div>
      <input
        type="text"
        value="soyisim"
        placeholder="soyisim"
        v-model="soyisim"
      />
    </div>

    <div>
      <input
        type="checkbox"
        id="mycheck"
        name="kontrol"
        value="kontrol"
        v-model="check"
      />
    </div>

    <div class="kimlik">
      <p class="text">{{ isim }}</p>
      <p class="text" v-if="!check">{{ soyisim }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      check: null,
      isim: null,
      soyisim: null,
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
