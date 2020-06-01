<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld :msg="msg"></HelloWorld>
  </div>
</template>

<script lang="ts">
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',

  components: {
    HelloWorld,
  },

  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>
