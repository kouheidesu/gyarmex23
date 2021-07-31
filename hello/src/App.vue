<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to COACHTECH"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
<template>
<div id="app">
<input type="text" v-model="text"/>
<p>{{text}}</p>
</div>
</template>

<script>
export default{
  data(){
    return{
      text:""
    };
  }
};
</script>
<style>

</style>
