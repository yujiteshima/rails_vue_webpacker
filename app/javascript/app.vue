<template>
  <div id="app">
    <p>{{ message }}</p>
    <h1>{{ message2}}</h1>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      message: "Hello Vue!",
      message2: "DreamsComeTrue!"
    };
  }
};
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
h1 {
  color: blue;
  text-align: center;
}
</style>
