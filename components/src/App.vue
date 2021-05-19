<template>
  <p v-if="age > 25">{{ msg }}</p>
  <p v-else>You must be at least 25 years old to view this message</p>
</template>

<script>
import Greeting from "./components/Greeting.vue";

  export default {
    name: "App",
    components: {
      Greeting
    },
  };
</script>

