<template>
  <div class="home bg-primary font-Poppins">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to  Vue.js App" />
  </div>
  <h1 class="font-black m-5">hellow</h1>
  <button class="bg-btnOrange">Submit</button>
  <h1 class="font-Roboto">helloworld</h1>
  <h1 class="font-Poppins">helloworld</h1>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>
