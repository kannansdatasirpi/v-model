<!--v-model directive-->
<template>
  <input type="text" v-model="name">  <!--3.then add an input element.then to bind data property to the input we use v-model directive-->
</template>

<script>
export default {
  name: 'App',
  components: {},
  data() {            //1.first empty data object
    return {
      name: ''        //2.lets begin adding element to user enter their input. so define data property called name and initialize empty string
    }
  },
  methods: {},
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
