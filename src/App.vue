<template>
  <div id="app">
    <div class="main">

      <div class="title">Create New Tasks</div>
      <div class="label">Name</div>

      <input type="text" value="name" placeholder="Write Name" v-model="name"/>

      <div class="label">Description</div>

      <input type="text" value="surname" placeholder="Write Surname" v-model="surname"/><br>
      
      <input class="date" placeholder="16"/>
      <input class="date" placeholder="Mart"/>
      <input class="date" placeholder="2000"/>
      
      <div class="label">Notification</div>
      <input placeholder="10 mins before"/><br>
      <button class="add-btn" @click="additems">ADD</button>

    </div>

    <p v-for="(item, index) in list" :key="index">
      {{ item }}
    </p>

  </div> 
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      name: null,
      surname: null,
      list: []
    }
  },
  methods: {
    additems() {
      this.list.push(JSON.stringify({name: this.name, surname: this.surname}))
      this.name = null
      this.surname = null
    }

  }

}



</script>

<style lang="scss" scoped>
@font-face {
  font-family: "Raleway";
  src: url("./assets/Raleway-Regular.ttf");
}
.main {
  width:336px;

  border: gray;
  border-style: solid;
  border-width: 20px;
  border-radius: 3px;

  padding-left: 27px;
  font-family: Raleway;
  font-style: normal;

  font-weight: normal;
  font-size: 14px;

  color: #050505;
}
.title {
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  
  margin-top: 25px;

  color: #050505;
}

input {
  margin-top: 12px;
  border-top: hidden;
  border-left: hidden;
  border-right: hidden;
  opacity: 0.55;
}

.label {
  font-weight: 600;
  font-size: 14px;
  margin-top: 30px;
}

.date{
  margin-top: 45px;
  width: 60px;
  margin-right: 5px;
}

.add-btn{
  margin-left: -27px;
  margin-top: 40px;
  width: 363px;
  height: 50px;

  background: #5A95FF;
  border-style: none;

  letter-spacing: 1px;
  font-weight: bold;
  font-size: 11px;
  color: #FFFFFF;
}
</style>
