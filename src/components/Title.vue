<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "La mia prima app con Vue CLI!",
    };
  },
};
</script>

<style scoped>
h1 {
  text-align: center;
}
</style>
