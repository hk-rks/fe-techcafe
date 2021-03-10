<template>
  <v-container>
    <HelloWorld :msg="msg" />
  </v-container>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  },
  data: () => ({
    msg: "Welcome to Your Vue.js App"
  })
};
</script>
