<template>
  <p>{{ msg }}</p>
</template>

<script>
export default {
  name: "Greeting",
  data() {
    return {
      msg: 'Yo world',
    };
  },
};
</script>

<style>

p {
  color: red;
}
</style>